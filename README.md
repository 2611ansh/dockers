# Dockers

**Use of Dockers:**

1. Environment Standardization (Can also be done via virtual machines {disadvantage: lack of elasticity})
2. Isolation
3. Portability
4. Build Once, Deploy Everywhere

## Download Link
You can download Docker from [this link](https://www.bing.com/ck/a?!&&p=8c75f5c389a5fbb6JmltdHM9MTY5NzUwMDgwMCZpZ3VpZD0wZjM0MDI0Mi0wNTRjLTY5ZjQtMzA4MC0xMWU5MDQ5OTY4NDkmaW5zaWQ9NTIwMA&ptn=3&hsh=3&fclid=0f340242-054c-69f4-3080-11e904996849&psq=docker+toolbox+for+windows+10&u=a1aHR0cHM6Ly9kb2NrZXItZG9jcy51Y2x2LmN1L3Rvb2xib3gvdG9vbGJveF9pbnN0YWxsX3dpbmRvd3Mv&ntb=1).

## Docker Commands

- `from`: Specify the base image.
- `copy`: Copy files from the host to the container.
- `expose`: Expose a specific port.
- `workdir`: Set the working directory inside the container.
- `run`: Execute a command.
- `cmd`: Define a default command to run when the container starts.

## Steps

1. Write the Docker File.
2. Building the Docker Image:
   ```
   docker build -t money_api .
   ```
3. Running the Docker Container:
   ```
   docker run -p 8080:8000 money_api
   ```

Make sure to replace the `8080:8000` with the desired port mapping.
