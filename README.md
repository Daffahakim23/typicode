# My JSON Server

This repository serves as a mock JSON server using [my-json-server](https://my-json-server.typicode.com/).

## Getting Started

Follow these steps to set up and use the JSON server:

### 1. Create a Repository on GitHub

1. Go to [GitHub](https://github.com/).
2. Click on the **New** button to create a new repository.
3. Name your repository `<your-repo>`.
4. Click on **Create repository**.

### 2. Create a `db.json` File

1. In your newly created repository, click on **Add file** and select **Create new file**.
2. Name the file `db.json`.
3. Add your JSON data to the file. For example:

    ```json
    {
      "posts": [
        { "id": 1, "title": "Hello World" }
      ],
      "comments": [
        { "id": 1, "body": "Nice post!", "postId": 1 }
      ]
    }
    ```

4. Commit the file to your repository.

### 3. Access Your Server

1. Visit `https://my-json-server.typicode.com/<your-username>/<your-repo>` to access your mock JSON server.
2. You can now make GET requests to your JSON server. For example:
    - `https://my-json-server.typicode.com/<your-username>/<your-repo>/posts`
    - `https://my-json-server.typicode.com/<your-username>/<your-repo>/comments`

## Example

Here's an example of how to use the JSON server:

```bash
curl https://my-json-server.typicode.com/<your-username>/<your-repo>/posts
