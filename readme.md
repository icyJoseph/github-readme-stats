# GitHub Readme Stats

## Features

-   [GitHub Stats Card](#github-stats-card)
-   [GitHub Extra Pins](#github-extra-pins)
-   [Top Languages Card](#top-languages-card)
-   [Themes](#themes)
    -   [Responsive Card Theme](#responsive-card-theme)
-   [Customization](#customization)
    -   [Common Options](#common-options)
    -   [Stats Card Exclusive Options](#stats-card-exclusive-options)
    -   [Repo Card Exclusive Options](#repo-card-exclusive-options)
    -   [Language Card Exclusive Options](#language-card-exclusive-options)
- [Keep your fork up to date](#keep-your-fork-up-to-date)   

## GitHub Stats Card

> This is a fork from https://github.com/anuraghazra/github-readme-stats
> It only allows my username


```md
[![icyJoseph's GitHub stats](https://github-readme-stats-9cjg.vercel.app/api?username=icyjoseph)](https://github.com/icyjoseph/github-readme-stats)
```

> **Note**
> Available ranks are S+ (top 1%), S (top 25%), A++ (top 45%), A+ (top 60%), and B+ (everyone). The values are calculated by using the [cumulative distribution function](https://en.wikipedia.org/wiki/Cumulative_distribution_function) using commits, contributions, issues, stars, pull requests, followers, and owned repositories. The implementation can be investigated at [src/calculateRank.js](./src/calculateRank.js).

### Hiding individual stats

You can pass a query parameter `&hide=` to hide any specific stats with comma-separated values.

> Options: `&hide=stars,commits,prs,issues,contribs`

```md
![icyJoseph's GitHub stats](https://github-readme-stats-9cjg.vercel.app/api?username=icyjoseph&hide=contribs,prs)
```

### Adding private contributions count to total commits count

You can add the count of all your private contributions to the total commits count by using the query parameter `&count_private=true`.

> **Note**
> If you are deploying this project yourself, the private contributions will be counted by default. If you are using the public Vercel instance, you need to choose to [share your private contributions](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/managing-contribution-settings-on-your-profile/showing-your-private-contributions-and-achievements-on-your-profile).

> Options: `&count_private=true`

```md
![icyJoseph's GitHub stats](https://github-readme-stats-9cjg.vercel.app/api?username=icyjoseph&count_private=true)
```
