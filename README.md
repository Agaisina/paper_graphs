# paper_graphs

Competition: https://codalab.lisn.upsaclay.fr/competitions/16684#learn_the_details-overview

The rapid growth of digital repositories and academic databases has led to an overwhelming abundance of scholarly articles. In the context of academic research, the task of categorizing these articles into genres or fields has become increasingly challenging. Assigning genres to academic papers, such as determining the specific area of study or field they belong to, is a crucial step for effective organization, searchability, and recommendation systems.

In this work, we aim to address the challenge of automatically assigning genres to academic papers by leveraging graph-based methods and label propagation techniques. Our approach capitalizes on the interconnected nature of academic content, where papers, authors, and words are linked in a complex web of relationships. We focus on three primary elements in our dataset: the title of the paper, the abstract, and the authorship information.

The structure of our dataset consists of academic papers, each associated with metadata including the title, abstract, and the authors involved. We recognize the interdisciplinary nature of many papers, making it a non-trivial task to categorize them accurately. To enhance our model's performance, we propose a comprehensive method that considers both the content of the papers and the relationships between authors and papers.

Our methodology involves constructing a graph-based representation of the academic network, where nodes represent papers, authors, and words, and edges signify relationships such as authorship and word occurrences. By incorporating graph-based algorithms, we can capture the inherent relationships within the academic domain. Additionally, we employ label propagation techniques to iteratively assign genres to papers based on their connections within the academic network.

To illustrate our approach, we present two distinct scenarios. First, we explore the assignment of genres to papers that lack explicit genre labels. Second, we delve into the propagation of genre information to papers with known genres but possibly incomplete or inaccurate labels.

Our work is motivated by the ambition to enhance the organization and discoverability of academic papers, facilitating more efficient literature reviews, targeted searches, and personalized recommendations. By proposing a model that leverages the interconnected nature of academic content, we contribute to the ongoing efforts in automating genre assignment and improving the accessibility of scholarly knowledge.

