# Function: <code>xdp_attachment_query</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xdp_attachment_query(struct xdp_attachment_info *info, struct netdev_bpf *bpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818e1420)
Location: net/core/xdp.c:382
Inline: False
```
**Symbols:**

```
ffffffff818e1420-ffffffff818e144f: xdp_attachment_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xdp_attachment_query(struct xdp_attachment_info *info, struct netdev_bpf *bpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff8192fc00)
Location: net/core/xdp.c:469
Inline: False
```
**Symbols:**

```
ffffffff8192fc00-ffffffff8192fc2f: xdp_attachment_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xdp_attachment_query(struct xdp_attachment_info *info, struct netdev_bpf *bpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81961e70)
Location: net/core/xdp.c:436
Inline: False
```
**Symbols:**

```
ffffffff81961e70-ffffffff81961e9f: xdp_attachment_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xdp_attachment_query(struct xdp_attachment_info *info, struct netdev_bpf *bpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a355f0)
Location: net/core/xdp.c:403
Inline: False
```
**Symbols:**

```
ffffffff81a355f0-ffffffff81a3561f: xdp_attachment_query (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int xdp_attachment_query(struct xdp_attachment_info *info, struct netdev_bpf *bpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffff800010c05cb8)
Location: net/core/xdp.c:436
Inline: False
```
**Symbols:**

```
ffff800010c05cb8-ffff800010c05d10: xdp_attachment_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xdp_attachment_query(struct xdp_attachment_info *info, struct netdev_bpf *bpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c0d1ecdc)
Location: net/core/xdp.c:436
Inline: False
Direct callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_ndo_bpf
```
**Symbols:**

```
c0d1ecdc-c0d1ed1c: xdp_attachment_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xdp_attachment_query(struct xdp_attachment_info *info, struct netdev_bpf *bpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (c000000000ceff70)
Location: net/core/xdp.c:436
Inline: False
```
**Symbols:**

```
c000000000ceff70-c000000000ceffb4: xdp_attachment_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xdp_attachment_query(struct xdp_attachment_info *info, struct netdev_bpf *bpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffe000784406)
Location: net/core/xdp.c:436
Inline: False
```
**Symbols:**

```
ffffffe000784406-ffffffe000784448: xdp_attachment_query (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int xdp_attachment_query(struct xdp_attachment_info *info, struct netdev_bpf *bpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81901e40)
Location: net/core/xdp.c:436
Inline: False
```
**Symbols:**

```
ffffffff81901e40-ffffffff81901e6f: xdp_attachment_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xdp_attachment_query(struct xdp_attachment_info *info, struct netdev_bpf *bpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff818bbc70)
Location: net/core/xdp.c:436
Inline: False
```
**Symbols:**

```
ffffffff818bbc70-ffffffff818bbc9f: xdp_attachment_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xdp_attachment_query(struct xdp_attachment_info *info, struct netdev_bpf *bpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81952e70)
Location: net/core/xdp.c:436
Inline: False
```
**Symbols:**

```
ffffffff81952e70-ffffffff81952e9f: xdp_attachment_query (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xdp_attachment_query(struct xdp_attachment_info *info, struct netdev_bpf *bpf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81974960)
Location: net/core/xdp.c:436
Inline: False
```
**Symbols:**

```
ffffffff81974960-ffffffff8197498f: xdp_attachment_query (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
