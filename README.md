# Mintlify Starter Kit

hi

Click on `Use this template` to copy the Mintlify starter kit. The starter kit contains examples including

![](https://kjfwgvfceqvbwpxdpzhy.supabase.co/storage/v1/object/public/user-uploads/0d2a1d5a-a5e5-4bad-b8aa-2e2e54b57a71/f3d3ad4a-2d3e-4566-8f57-c27a597c4507-Screenshot%202023-11-08%20at%2011.32.07.png)- Guide pages
- Navigation
- Customizations
- API Reference pages
- Use of popular components

### 👩‍💻 Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mintlify) to preview the documentation changes locally. To install, use the following command

```
npm i -g mintlify
```

Run the following command at the root of your documentation (where mint.json is)

```
mintlify dev
```

### 😎 Publishing Changes

Changes will be deployed to production automatically after pushing to the default branch.

You can also preview changes using PRs, which generates a preview link of the docs.

#### Troubleshooting

- Mintlify dev isn't running - Run `mintlify install` it'll re-install dependencies.
- Page loads as a 404 - Make sure you are running in a folder with `mint.json`