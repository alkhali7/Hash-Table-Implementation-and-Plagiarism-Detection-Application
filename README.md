# Custom Hash Table Implementation and Its Application in Plagiarism Detection

## Description

This project involves the development of a hash table (dictionary) from scratch in Python, showcasing the ability to perform insertions, deletions, and lookups with expected O(1) runtime. The implementation is applied to an innovative application problem - detecting plagiarism in musical compositions.

## Project Files
- HashTable_isPlagiarism.py : full implementation of the Hash Table and application problem.

## Background

Hash Tables are fundamental data structures in computer science, known for their efficiency in data storage and retrieval. They are particularly useful in scenarios where fast access to data is crucial. This project not only explores the intricacies of creating a hash table but also applies this knowledge to solve a real-world problem in the music industry.

## Implementation Details

**Complete Hash Table Implementation**: Development of a custom hash table, capable of handling typical operations like insertion, deletion, and lookup efficiently.

**Collision Resolution**: Implementing double hashing for effective collision resolution, ensuring the reliability of the hash table even in high load factor scenarios.

**Dynamic Resizing**: The hash table supports dynamic resizing, growing and shrinking in response to the number of elements stored, optimizing memory usage.

**Protected and Magic Methods**: Utilization of protected methods for internal logic and magic methods to provide an intuitive interface for hash table operations.

**Application Problem**: Plagiarism Detection in Music

**Background**: Addressing the issue of song plagiarism in the music industry, particularly for a record label "Hippity Hoppity".

**Music Representation**: Songs are represented as lists of melodies, with each melody being a list of integers symbolizing musical notes.

**Plagiarism Criteria**: Plagiarism is determined based on the similarity of melodies, considering key signatures and melody length.

**is_plagiarism Function**: Implementation of a function to determine if a song plagiarizes another based on the number of similar melodies and a specified threshold for maximum similarity.

## Key Features

**Efficient Data Handling**: The hash table ensures fast data retrieval, insertion, and deletion, crucial for large datasets.

**Plagiarism Detection**: The application problem demonstrates the practical use of hash tables in identifying similar patterns in music, a valuable tool for copyright enforcement in the music industry.

## Technologies Used

Python

Hash Table (Custom Implementation)

Music Theory (for Plagiarism Detection)

## Setup and Installation

1. Clone the repository to your local machine.
2. Ensure Python is installed on your system.
3. Navigate to the project directory.
4. Run the provided implementation file to test the hash table functionality and plagiarism detection.

## Usage

The hash table can be used in various applications where quick data access is necessary.

The plagiarism detection algorithm can be applied to compare musical compositions for potential copyright infringements.

## Contributions

Developed by: Shams Alkhalidy

Inspired by challenges in data management and the need for efficient data structures in the digital age.



## Contact

For inquiries, please contact alkhali7@msu.edu
