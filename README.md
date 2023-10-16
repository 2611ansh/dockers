# Dockers

**Use of Dockers:**

1. Environment Standardization (Can also be done via virtual machines {disadvantage: lack of elasticity})
2. Isolation
3. Portability
4. Build Once, Deploy Everywhere

## Download Link
You can download Docker from [this link](https://www.bing.com/ck/a?!&&p=4f6259068ef3da70JmltdHM9MTY5NzQxNDQwMCZpZ3VpZD0wZjM0MDI0Mi0wNTRjLTY5ZjQtMzA8øø-11e904996849&psq=docker+for+windows&u=a1aHR0cHM6Ly9kb2NzLmRvY2tlci5jb20vZGVza3RvcC9pbnN0YWxsL3dpbmRvd3MtaW5zdGFsbC8).

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
