# Function: <code>bpf_xdp_link_show_fdinfo</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_xdp_link_show_fdinfo(const struct bpf_link *link, struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819ffca0)
Location: net/core/dev.c:9329
Inline: False
```
**Symbols:**

```
ffffffff819ffca0-ffffffff819ffcea: bpf_xdp_link_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_xdp_link_show_fdinfo(const struct bpf_link *link, struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e63e0)
Location: net/core/dev.c:9588
Inline: False
```
**Symbols:**

```
ffffffff819e63e0-ffffffff819e642a: bpf_xdp_link_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_xdp_link_show_fdinfo(const struct bpf_link *link, struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a96910)
Location: net/core/dev.c:9589
Inline: False
```
**Symbols:**

```
ffffffff81a96910-ffffffff81a9695a: bpf_xdp_link_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_xdp_link_show_fdinfo(const struct bpf_link *link, struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0d780)
Location: net/core/dev.c:9327
Inline: False
```
**Symbols:**

```
ffffffff81c0d780-ffffffff81c0d7d3: bpf_xdp_link_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_xdp_link_show_fdinfo(const struct bpf_link *link, struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbd3d0)
Location: net/core/dev.c:9314
Inline: False
```
**Symbols:**

```
ffffffff81dbd3d0-ffffffff81dbd423: bpf_xdp_link_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_xdp_link_show_fdinfo(const struct bpf_link *link, struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2dc00)
Location: net/core/dev.c:9326
Inline: False
```
**Symbols:**

```
ffffffff81e2dc00-ffffffff81e2dc53: bpf_xdp_link_show_fdinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_xdp_link_show_fdinfo(const struct bpf_link *link, struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eebf50)
Location: net/core/dev.c:9444
Inline: False
```
**Symbols:**

```
ffffffff81eebf50-ffffffff81eebfa3: bpf_xdp_link_show_fdinfo (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
