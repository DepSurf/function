# Function: <code>calc_map_type_and_dist</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum pci_p2pdma_map_type calc_map_type_and_dist(struct pci_dev *provider, struct pci_dev *client, int *dist, bool verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff8191c820)
Location: drivers/pci/p2pdma.c:574
Inline: False
Direct callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:pci_p2pdma_distance_many
```
**Symbols:**

```
ffffffff8191c820-ffffffff8191cc4e: calc_map_type_and_dist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum pci_p2pdma_map_type calc_map_type_and_dist(struct pci_dev *provider, struct pci_dev *client, int *dist, bool verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff8195fde0)
Location: drivers/pci/p2pdma.c:576
Inline: False
Direct callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:pci_p2pdma_distance_many
```
**Symbols:**

```
ffffffff8195fde0-ffffffff8196020c: calc_map_type_and_dist (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum pci_p2pdma_map_type calc_map_type_and_dist(struct pci_dev *provider, struct pci_dev *client, int *dist, bool verbose);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/p2pdma.c (ffffffff819a94d0)
Location: drivers/pci/p2pdma.c:575
Inline: False
Direct callers:
  - drivers/pci/p2pdma.c:pci_p2pdma_map_segment
  - drivers/pci/p2pdma.c:pci_p2pdma_distance_many
```
**Symbols:**

```
ffffffff819a94d0-ffffffff819a98f8: calc_map_type_and_dist (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
