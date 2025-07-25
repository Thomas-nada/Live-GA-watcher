# Cardano Governance Proposal Viewer

[](https://thomas-nada.github.io/Live-GA-watcher/)

A simple, responsive, client-side web tool to view, filter, and sort active Cardano governance proposals. This project translates the functionality of a command-line script into an interactive and visually pleasing web interface.

-----

## ✨ Features

  * **Live Data**: Fetches the latest active proposals directly from the [Koios REST API](https://koios.rest/).
  * **Visual Interface**: Displays each proposal in a clean card format.
  * **Progress Visualization**: Shows the DRep "Yes" vote percentage with a progress bar.
  * **Approval Threshold**: A visual line indicates the 67% threshold required for a proposal to pass.
  * **Dynamic Filtering**: Instantly filter proposals by typing a keyword in the search bar.
  * **Advanced Sorting**: Sort proposals by:
      * Highest / Lowest "Yes" Percentage
      * Most / Fewest "Yes" Votes Cast
  * **External Links**: Each proposal ID links directly to its page on [gov.tools](https://gov.tools/) for deeper analysis.
  * **Responsive Design**: Looks great on desktop, tablet, and mobile devices.

-----

## 🚀 How to Use

Access the tool directly in your browser by visiting the **[Live Demo](https://thomas-nada.github.io/Live-GA-watcher/)**.

1.  Use the search bar at the top to filter proposals by title.
2.  Use the dropdown menu to change the sorting order.
3.  Click on a proposal's ID to view it on `gov.tools`.

-----

## 🛠️ Built With

  * **HTML5**
  * **Tailwind CSS** for styling.
  * **Vanilla JavaScript** for all logic and API interactions.
  * **Koios API** as the data source.
  * **corsproxy.io** to handle CORS issues in the browser.

-----

## 🙏 Attribution

This tool is a web-based implementation inspired by the powerful governance scripts provided by IntersectMBO.

  * **Original Script**: [query-live-actions.sh](https://github.com/IntersectMBO/governance-scripts/blob/main/scripts/query-live-actions.sh)
  * **Original Author**: [Ryun1](https://github.com/IntersectMBO/governance-scripts/commits?author=Ryun1)
