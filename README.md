# parrott

## Personal webpage

This has a protected main branch 

All updates should be placed in a new branch then PR opened to merge to Lab the that will build on CF to [https://www.parrottlab.xyz](https://parrottlab.xyz)

Then when confirmed that is good PR can be opened for Lab to Main merge this then will be available on [https://www.parrott.xyz](https://www.parrott.xyz)

### Flow 

1. Create a feature branch off lab

```bash
git checkout lab
git pull
git checkout -b feature/some-new-feature
```

2. Do your work, then push and open a PR to `lab`

```bash
git push -u origin feature/some-new-feature
```

Then go to GitHub and open a Pull Request to `lab`

3. After testing on lab, open a PR from lab to main