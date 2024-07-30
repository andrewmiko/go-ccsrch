## Description:

go-ccsrch is an open-source, high-performance tool developed in Go for searching and identifying credit card patterns within file systems, including binary files. It is a modern replacement for the deprecated CCSRCH software, leveraging Go’s efficiency and concurrency features to perform fast and comprehensive searches. The tool includes a built-in list of common credit card patterns and allows users to extend these patterns through a YAML configuration file. It is ideal for security audits, data protection compliance, and sensitive data discovery.

## Features:
- Pre-Defined Patterns: Includes a default set of regular expressions for common credit card formats.
- Configurable Patterns: Users can extend the search patterns by providing additional regex patterns through a YAML configuration file.
- Filesystem Scanning: Capable of scanning all file types, including binary files, to detect credit card numbers.
- Performance: Optimized for speed and efficiency using Go’s concurrency features.
- Cross-Platform: Available for multiple architectures, including ARM64, x86_64, and more.
- Docker Integration: Provides Docker images for easy deployment in containerized environments.
- Open Source: Licensed under the MIT License.
