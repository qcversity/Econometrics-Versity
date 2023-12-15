# Econometrics Versity

The **Econometrics Versity**, is a comprehensive resource for learning and applying econometrics using the Python programming language. This repository serves as an interactive book, offering a blend of theory and practical examples to help you master econometrics.

### What You'll Find Here

- **Theory**: Understand the fundamental concepts of econometrics, including statistical methods and economic theories.
- **Python Examples**: Explore practical examples using Python to analyze and interpret economic data.
- **Interactive Notebooks**: Hands-on Jupyter Notebooks that allow you to see econometrics in action.
- **Resources**: Additional materials for deeper learning and exploration.

## Getting Started

To get started with Econometrics Versity:

### Clone the repository to your local machine.

```
git clone https://github.com/qcversity/Econometrics-Versity.git
```

or

```
gh repo clone qcversity/Econometrics-Versity
```

### Setup The Environment

In this section you will be guided on how to set up your environment using three tools, `mamba`, `conda` and `venv`. Feel free to use any other tool you use in your development.

#### Using `Mamba` Package Manager

1. Create a virtual environment using the `environment.yml` file

```
mamba env create -f environment.yml
```

Alternatively you can use the next command to create the environment:

```
mamba env create -f requirements.txt -n EconVersity
```

2. Activate the newly created virtual environment

```
mamba activate EconVersity
```


#### Using `conda`

If `conda` is your main package manager you can set up your environment using the following command:

```
conda create -n EconVersity --file package-list.txt
```

#### Using `venv` Virtual Environment Tool

If you are using native Python tool `venv` for virtual environment:

1. Create a folder for this project, please use a command Line Interpreter such as Terminal or Windows command prompt:

```
mkdir EconVersity
```

Go this created directory

```
cd EconVersity
```

2. Create a virtual environment first:

```
python -m venv venv
```

3. Activate the virtual environment

On Linux-Based systems:
```
source venv/bin/activate
```

On Windows system:

```
venv\Scripts\activate
```

4. Install the dependencies

```
python -m pip install -r requirements.txt
```


### How to Use This Learning Space

This learning space has just launched, and while writing the content, they will be lectures and interactive sessions in the form of Jupyter Notebooks:

1. First you need to read the lectures
2. Navigate to the Jupyter Notebooks for interactive sessions.
3. Solutions will be available in Notebooks Solutions

## Contributing

We welcome contributions to Econometrics Versity! If you're interested in contributing, here's how you can do it:
1. **Fork the Repository**: Start by forking the repository to your GitHub account.
2. **Make Your Changes**: Add your content, fix bugs, or implement new features.
3. **Submit a Pull Request**: After making your changes, submit a pull request to the main repository.
4. **Code Review**: Your changes will be reviewed, and if everything is in order, they will be merged into the project.

When contributing, please follow these guidelines:
  - Ensure your code is well-documented.
  - Adhere to the existing coding style and standards.
  - Update the documentation if you're adding new features or making changes that affect how users interact with the project.

## License
Econometrics Versity is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For questions or feedback, please open an issue in the repository, or contact us directly via [email me](mailto:qcversity.info@gmail.com).

