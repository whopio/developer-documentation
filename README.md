<p align="center">
  <a href="https://apps.whop.com">
    <h1 align="center">Whop Developer Documentation</h1>
  </a>
</p>

---

This ReadMe provides instructions on how to edit the Whop Developer documentation.

## Development

We use [Mintlify](https://mintlify.com/) for our documentation. To run the documentation locally on your machine, you will need to install their CLI.

Use the following command:

```
npm i -g mintlify
```

Once you have installed the CLI, you can now start making your changes. After you have cloned the repository, run the following command at the root of the project (where the `mint.json` file is)

```
mintlify dev
```

This will run the documentation on `localhost:3000`, head there and you will see the documentation!

### Adding new pages

If you are creating new pages, you will also need to add them to the navigation. To do this, head to the `mint.json` file. This is where all the navigation configuration lives.Find the relevant group, and add in the path of your new page.

To learn more about navigation, head to the [Mintlify Documentation](https://mintlify.com/docs/settings/navigation)

## Review Process

Once you've submitted your contribution, the Whop team will review your changes, provide feedback, and merge the pull request when it's ready.

Please let us know if you have any questions or need further assistance in your PR's comments.
