# Function: <code>bpf_xdp_link_update</code>

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
int bpf_xdp_link_update(struct bpf_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a02070)
Location: net/core/dev.c:9358
Inline: False
```
**Symbols:**

```
ffffffff81a02070-ffffffff81a02167: bpf_xdp_link_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_xdp_link_update(struct bpf_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e8da0)
Location: net/core/dev.c:9617
Inline: False
```
**Symbols:**

```
ffffffff819e8da0-ffffffff819e8e97: bpf_xdp_link_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_xdp_link_update(struct bpf_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a99d10)
Location: net/core/dev.c:9618
Inline: False
```
**Symbols:**

```
ffffffff81a99d10-ffffffff81a99e2b: bpf_xdp_link_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_xdp_link_update(struct bpf_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c11820)
Location: net/core/dev.c:9356
Inline: False
```
**Symbols:**

```
ffffffff81c11820-ffffffff81c11948: bpf_xdp_link_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_xdp_link_update(struct bpf_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dc1800)
Location: net/core/dev.c:9343
Inline: False
```
**Symbols:**

```
ffffffff81dc1800-ffffffff81dc1928: bpf_xdp_link_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_xdp_link_update(struct bpf_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e31210)
Location: net/core/dev.c:9355
Inline: False
```
**Symbols:**

```
ffffffff81e31210-ffffffff81e31338: bpf_xdp_link_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_xdp_link_update(struct bpf_link *link, struct bpf_prog *new_prog, struct bpf_prog *old_prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81eef720)
Location: net/core/dev.c:9473
Inline: False
```
**Symbols:**

```
ffffffff81eef720-ffffffff81eef83b: bpf_xdp_link_update (STB_LOCAL)
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
