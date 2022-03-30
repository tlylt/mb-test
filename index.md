<frontmatter>
  layout: default.md
  pageNav: 2
  pageNavTitle: "Chapters of This Page"
</frontmatter>

<br>

Using action

<div class="jumbotron jumbotron-fluid bg-primary text-white">
  <div class="container">
    <h1 class="display-4 no-index">This is a test page</h1>
    <p class="lead">A tagline can go here</p>
  </div>
</div>

# Heading 1
Keep files

**A list:**

* item A
* item B
  1. item b1
  1. item b2

**A `code` example:**

```html
<foo>
  <bar type="name">goo</bar>
</foo>
```

<canvas id="myChart" width="500" height="200"></canvas>

<div>Hello</div>

## Sub Heading 1.1

A <tooltip content=":exclamation: some **important explanation**" placement="top" trigger="hover">tooltip</tooltip>, a <trigger for="modal:modalinfo" trigger="click">modal</trigger>, a <a href="https://markbind.org/">link</a>, a <span class="badge badge-danger">badge</span>, another <span class="badge badge-warning">badge</span>.

<modal header="Modal Title" id="modal:modalinfo">
Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text some text some text some text some text some text some text some text. Some text some text some text some text some text some text. Some text some text some text some text some text some text some text.
</modal>

**A table:**

Column 1 | Column 2 | Column 3 | :far-thumbs-up: / :far-thumbs-down:?
:------: | :------: | :------: | ----
value1   | x        | 5        | :far-thumbs-up:
value2   | y        | 20       | :far-thumbs-down:


## Sub Heading 1.2

**Media embeds:**

@[youtube](http://www.youtube.com/watch?v=v40b3ExbM0c)

**Tabs:**

<tabs>
  <tab header="Tab X">
    Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text some text some text some text some text some text some text some text. Some text some text some text some text some text some text. Some text some text some text some text some text some text some text.
  </tab>
  <tab header="Tab Y">
    ...
  </tab>
  <tab-group header="Tab group">
    <tab header="Tab Y.1">
      ...
    </tab>
    <tab header="Tab Y.2">
      ...
    </tab>
  </tab-group>
</tabs>

<br>

**Some boxes:**

<box type="info">
    info
</box>
<box type="warning" dismissible>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</box>
<box type="tip" header="Tip box heading">
    tip
</box>
<box type="success" header="Tip box heading">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</box>
<box type="important" dismissible header="Tip box heading">
    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</box>

<br>

# Heading 3

<panel header="Expandable panel" type="info">
  Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text. Some text some text some text some text some text some text some text some text some text some text some text some text some text some text. Some text some text some text some text some text some text. Some text some text some text some text some text some text some text.
</panel>
<br>
<panel header="Expanded panel" alt="Minimized panel" type="success" minimized>
  ...
</panel>
<br>
<panel header="Expanded panel" alt="Minimized panel" type="seamless">
  ...
</panel>
<br>

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
<panel header="___Minimal panel **->**___" type="minimal" alt="Minimal panel" popup-url="https://markbind.org/userGuide/components/presentation.html#panels" no-switch>
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</panel>

Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/3.7.1/chart.min.js"></script>

<script>
const ctx = document.getElementById('myChart');
const myChart = new Chart(ctx, {
    type: 'bar',
    data: {
        labels: ['Red', 'Blue', 'Yellow', 'Green', 'Purple', 'Orange'],
        datasets: [{
            label: '# of Votes',
            data: [12, 19, 3, 5, 2, 3],
            backgroundColor: [
                'rgba(255, 99, 132, 0.2)',
                'rgba(54, 162, 235, 0.2)',
                'rgba(255, 206, 86, 0.2)',
                'rgba(75, 192, 192, 0.2)',
                'rgba(153, 102, 255, 0.2)',
                'rgba(255, 159, 64, 0.2)'
            ],
            borderColor: [
                'rgba(255, 99, 132, 1)',
                'rgba(54, 162, 235, 1)',
                'rgba(255, 206, 86, 1)',
                'rgba(75, 192, 192, 1)',
                'rgba(153, 102, 255, 1)',
                'rgba(255, 159, 64, 1)'
            ],
            borderWidth: 1
        }]
    },
    options: {
        scales: {
            y: {
                beginAtZero: true
            }
        }
    }
});
</script>

<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>
<script>
   mermaid.initialize({ startOnLoad: true });
</script>

Here is one mermaid diagram:
<div class="mermaid">
   graph TD 
   A[Client] --> B[Load Balancer] 
   B --> C[Server1] 
   B --> D[Server2]
</div>

And here is another:
<div class="mermaid">
   graph TD 
   A[Client] -->|tcp_123| 
   B(Load Balancer) 
   B -->|tcp_456| C[Server1] 
   B -->|tcp_456| D[Server2]
</div>
