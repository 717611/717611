# Client Details Form

A standalone client intake page for collecting contact details, project needs, timeline, budget, and a short project summary.

## Preview locally

You can preview the form with any static file server. From this repository, run:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000> in your browser.

## Deploy on Vercel

Yes, this can be deployed on Vercel as a static site.

1. Push this repository to GitHub, GitLab, or Bitbucket.
2. In Vercel, choose **Add New > Project** and import the repository.
3. Keep the framework preset as **Other** or **Static**.
4. Leave the build command blank because this form is plain HTML and CSS.
5. Leave the output directory as the project root.
6. Deploy.

## Full-stack note

This page is currently frontend-only. To make it full stack, connect the form to a backend endpoint or serverless function that stores submissions and sends notifications.
