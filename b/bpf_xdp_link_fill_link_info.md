# Function: <code>bpf_xdp_link_fill_link_info</code>

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
int bpf_xdp_link_fill_link_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819fee70)
Location: net/core/dev.c:9343
Inline: False
```
**Symbols:**

```
ffffffff819fee70-ffffffff819feeab: bpf_xdp_link_fill_link_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_xdp_link_fill_link_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e5710)
Location: net/core/dev.c:9602
Inline: False
```
**Symbols:**

```
ffffffff819e5710-ffffffff819e574b: bpf_xdp_link_fill_link_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_xdp_link_fill_link_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a95bc0)
Location: net/core/dev.c:9603
Inline: False
```
**Symbols:**

```
ffffffff81a95bc0-ffffffff81a95bfb: bpf_xdp_link_fill_link_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_xdp_link_fill_link_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0c5a0)
Location: net/core/dev.c:9341
Inline: False
```
**Symbols:**

```
ffffffff81c0c5a0-ffffffff81c0c5e3: bpf_xdp_link_fill_link_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_xdp_link_fill_link_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbc360)
Location: net/core/dev.c:9328
Inline: False
```
**Symbols:**

```
ffffffff81dbc360-ffffffff81dbc3a3: bpf_xdp_link_fill_link_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_xdp_link_fill_link_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e2cb70)
Location: net/core/dev.c:9340
Inline: False
```
**Symbols:**

```
ffffffff81e2cb70-ffffffff81e2cbb3: bpf_xdp_link_fill_link_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_xdp_link_fill_link_info(const struct bpf_link *link, struct bpf_link_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eeade0)
Location: net/core/dev.c:9458
Inline: False
```
**Symbols:**

```
ffffffff81eeade0-ffffffff81eeae23: bpf_xdp_link_fill_link_info (STB_LOCAL)
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
