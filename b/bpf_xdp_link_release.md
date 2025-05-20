# Function: <code>bpf_xdp_link_release</code>

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
void bpf_xdp_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a02430)
Location: net/core/dev.c:9299
Inline: False
Direct callers:
  - net/core/dev.c:bpf_xdp_link_detach
```
**Symbols:**

```
ffffffff81a02430-ffffffff81a0246e: bpf_xdp_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_xdp_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e9660)
Location: net/core/dev.c:9558
Inline: False
Direct callers:
  - net/core/dev.c:bpf_xdp_link_detach
```
**Symbols:**

```
ffffffff819e9660-ffffffff819e97d4: bpf_xdp_link_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void bpf_xdp_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9559
Inline: False
Direct callers:
  - net/core/dev.c:bpf_xdp_link_detach
```
**Symbols:**

```
ffffffff81a9a2d0-ffffffff81a9a453: bpf_xdp_link_release (STB_LOCAL)
ffffffff81d35fca-ffffffff81d35fdf: bpf_xdp_link_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void bpf_xdp_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9297
Inline: False
Direct callers:
  - net/core/dev.c:bpf_xdp_link_detach
```
**Symbols:**

```
ffffffff81c11950-ffffffff81c11b22: bpf_xdp_link_release (STB_LOCAL)
ffffffff81f02742-ffffffff81f02757: bpf_xdp_link_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void bpf_xdp_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9284
Inline: False
Direct callers:
  - net/core/dev.c:bpf_xdp_link_detach
```
**Symbols:**

```
ffffffff81dc1af0-ffffffff81dc1cc2: bpf_xdp_link_release (STB_LOCAL)
ffffffff820ab374-ffffffff820ab389: bpf_xdp_link_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void bpf_xdp_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9296
Inline: False
Direct callers:
  - net/core/dev.c:bpf_xdp_link_detach
```
**Symbols:**

```
ffffffff81e31880-ffffffff81e31a52: bpf_xdp_link_release (STB_LOCAL)
ffffffff8212c9e7-ffffffff8212c9fc: bpf_xdp_link_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void bpf_xdp_link_release(struct bpf_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:9414
Inline: False
Direct callers:
  - net/core/dev.c:bpf_xdp_link_detach
```
**Symbols:**

```
ffffffff81eef850-ffffffff81eefa19: bpf_xdp_link_release (STB_LOCAL)
ffffffff8220e712-ffffffff8220e727: bpf_xdp_link_release.cold (STB_LOCAL)
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
