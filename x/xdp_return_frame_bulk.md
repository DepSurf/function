# Function: <code>xdp_return_frame_bulk</code>

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
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xdp_return_frame_bulk(struct xdp_frame *xdpf, struct xdp_frame_bulk *bq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/xdp.c (ffffffff81a38760)
Location: net/core/xdp.c:411
Inline: True
```
**Symbols:**

```
ffffffff81a38760-ffffffff81a38822: xdp_return_frame_bulk.part.0 (STB_LOCAL)
ffffffff81a38830-ffffffff81a38858: xdp_return_frame_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void xdp_return_frame_bulk(struct xdp_frame *xdpf, struct xdp_frame_bulk *bq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81a1fa20)
Location: net/core/xdp.c:412
Inline: True
```
**Symbols:**

```
ffffffff81a1fa20-ffffffff81a1fb04: xdp_return_frame_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void xdp_return_frame_bulk(struct xdp_frame *xdpf, struct xdp_frame_bulk *bq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81ad3ba0)
Location: net/core/xdp.c:413
Inline: True
```
**Symbols:**

```
ffffffff81ad3ba0-ffffffff81ad3c84: xdp_return_frame_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void xdp_return_frame_bulk(struct xdp_frame *xdpf, struct xdp_frame_bulk *bq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81c51bc0)
Location: net/core/xdp.c:472
Inline: True
```
**Symbols:**

```
ffffffff81c51bc0-ffffffff81c51ee1: xdp_return_frame_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void xdp_return_frame_bulk(struct xdp_frame *xdpf, struct xdp_frame_bulk *bq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/xdp.c (ffffffff81e06f90)
Location: net/core/xdp.c:470
Inline: True
```
**Symbols:**

```
ffffffff81e06f90-ffffffff81e0714e: xdp_return_frame_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xdp_return_frame_bulk(struct xdp_frame *xdpf, struct xdp_frame_bulk *bq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/xdp.c (ffffffff81e79280)
Location: net/core/xdp.c:472
Inline: True
```
**Symbols:**

```
ffffffff81e79280-ffffffff81e79597: xdp_return_frame_bulk.part.0 (STB_LOCAL)
ffffffff81e798f0-ffffffff81e7991d: xdp_return_frame_bulk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void xdp_return_frame_bulk(struct xdp_frame *xdpf, struct xdp_frame_bulk *bq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/xdp.c (ffffffff81f39310)
Location: net/core/xdp.c:472
Inline: True
```
**Symbols:**

```
ffffffff81f39310-ffffffff81f39627: xdp_return_frame_bulk.part.0 (STB_LOCAL)
ffffffff81f39a10-ffffffff81f39a3d: xdp_return_frame_bulk (STB_GLOBAL)
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
