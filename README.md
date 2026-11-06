# Vandalizer Training Hub

A browser-based training hub for [Vandalizer](https://vandalizer.uidaho.edu/docs), the AI document platform for research administration created by [AI4RA](https://ai4ra.uidaho.edu/) at the University of Idaho.

## Modules

1. **Vandalizer Feature Guides**: step-by-step guides with screenshots for each feature
2. **AI Literacy Foundations**
3. **Enterprise Deployment**: running Vandalizer at your institution
4. **MindRouter Deployment**: self-hosting models with [MindRouter](https://mindrouter.ai/) and connecting Vandalizer to it

## Running it

It's a static site: open `index.html` through any web server. On Windows, with no other tools installed:

```powershell
powershell -ExecutionPolicy Bypass -File serve.ps1
```

Then open http://localhost:8765. Lesson progress is saved in the browser.

## Credits

Vandalizer is created by AI4RA: Artificial Intelligence for Research Administration, University of Idaho. This material is based upon work supported by the National Science Foundation under Award No. 2427549.
