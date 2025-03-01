### Scoop Buckets

A simple Scoop software bucket repository.

## Directory Structure

- `bucket/` - Contains all software package definition files.
- `scripts/` - Contains auxiliary scripts.
- `README.md` - Project description file.

## How to Use

1. Install [Scoop](https://scoop.sh/)
2. Add this bucket repository:
    ```sh
    scoop bucket add bai_scoop-buckets https://github.com/lovebai/scoop-buckets
    ```
3. Install software packages:
    ```sh
    scoop install bai_scoop-buckets/<package-name>
    ```

## Contribution Guide

Contributions are welcome via Pull Requests to add new software packages or improve existing ones. Please follow the guidelines below:

1. Fork this repository
2. Create a new branch
3. Submit your changes
4. Create a Pull Request

## License

This project is licensed under the [Apache License 2.0](LICENSE).
