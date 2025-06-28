# OSINT Framework

This is a web-based framework for Open Source Intelligence (OSINT). It provides a graph-based visualization of various OSINT resources and tools.

## Features

- **Interactive Graph:** Visualizes OSINT tools and resources as a tree graph.
- **Search:** Filter nodes by name or description.
- **Dark Mode:** A comfortable viewing mode for low-light environments.
- **Categorized Resources:** Resources are grouped into logical categories.

## Getting Started

1.  Clone the repository:
    ```bash
    git clone https://github.com/lockfale/osint-framework.git
    ```
2.  Navigate to the `public` directory.
3.  Open `index.html` in your web browser.

## How to Use

- **Click on nodes** to expand or collapse categories.
- **Click on links** to open the corresponding resource in a new tab.
- **Use the search bar** to filter the graph.
- **Toggle the dark mode switch** for a different theme.

## Legend

- **(T)**: Indicates a tool that must be installed and run locally.
- **(D)**: Google Dork.
- **(R)**: Requires registration.
- **(M)**: Indicates a URL that contains the search term and the URL itself must be edited manually.

## Contributing

Contributions, feedback, and suggestions are welcome! Please feel free to open an issue or pull request on the [GitHub repository](https://github.com/lockfale/osint-framework).

## Notes
OSINT framework focused on gathering information from free tools or resources. The intention is to help people find free OSINT resources. Some of the sites included might require registration or offer more data for $$$, but you should be able to get at least a portion of the available information for no cost.

I originally created this framework with an information security point of view. Since then, the response from other fields and disciplines has been incredible. I would love to be able to include any other OSINT resources, especially from fields outside of infosec. Please let me know about anything that might be missing!

Please visit the framework at the link below and good hunting!

https://osintframework.com

### For Update Notifications
Follow me on Twitter: @jnordine - https://twitter.com/jnordine  
Watch or star the project on Github: https://github.com/lockfale/osint-framework

### Suggestions, Comments, Feedback
Feedback or new tool suggestions are extremely welcome!  Please feel free to submit a pull request or open an issue on github or reach out on Twitter.

### Contribute with a GitHub Pull Request
For new resources, please ensure that the site is available for public and free use.
<ol start="1">
  <li>Update the arf.json file in the format shown below. If this isn't the first entry for a folder, add a comma to the last closing brace of the previous entry.</li>
</ol>

```
{
  "name": "Example Name",
  "type": "url",
  "url": "http://example.com"
}
```

<ol start="2">
  <li>Submit pull request!</li>
</ol>

Thank you!

## OSINT Framework Website

https://osintframework.com

Happy Hunting!