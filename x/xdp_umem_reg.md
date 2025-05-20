# Function: <code>xdp_umem_reg</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff819ccfe7)
Location: net/xdp/xdp_umem.c:259
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a06237)
Location: net/xdp/xdp_umem.c:310
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a75b66)
Location: net/xdp/xdp_umem.c:300
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81aac9ea)
Location: net/xdp/xdp_umem.c:340
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xdp_umem_reg(struct xdp_umem *umem, struct xdp_umem_reg *mr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ba8390)
Location: net/xdp/xdp_umem.c:304
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81ba8390-ffffffff81ba8663: xdp_umem_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xdp_umem_reg(struct xdp_umem *umem, struct xdp_umem_reg *mr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81bb8120)
Location: net/xdp/xdp_umem.c:154
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81bb8120-ffffffff81bb83ae: xdp_umem_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xdp_umem_reg(struct xdp_umem *umem, struct xdp_umem_reg *mr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ba72e0)
Location: net/xdp/xdp_umem.c:154
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81ba72e0-ffffffff81ba756c: xdp_umem_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xdp_umem_reg(struct xdp_umem *umem, struct xdp_umem_reg *mr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81c74e40)
Location: net/xdp/xdp_umem.c:153
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81c74e40-ffffffff81c751ef: xdp_umem_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xdp_umem_reg(struct xdp_umem *umem, struct xdp_umem_reg *mr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81e19060)
Location: net/xdp/xdp_umem.c:153
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81e19060-ffffffff81e19342: xdp_umem_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xdp_umem_reg(struct xdp_umem *umem, struct xdp_umem_reg *mr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ff0200)
Location: net/xdp/xdp_umem.c:151
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff81ff0200-ffffffff81ff0608: xdp_umem_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xdp_umem_reg(struct xdp_umem *umem, struct xdp_umem_reg *mr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff8206c3a0)
Location: net/xdp/xdp_umem.c:151
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff8206c3a0-ffffffff8206c7b6: xdp_umem_reg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xdp_umem_reg(struct xdp_umem *umem, struct xdp_umem_reg *mr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff82140180)
Location: net/xdp/xdp_umem.c:156
Inline: False
Direct callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
**Symbols:**

```
ffffffff82140180-ffffffff821405d3: xdp_umem_reg (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffff800010d812c8)
Location: net/xdp/xdp_umem.c:340
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (c0e7b820)
Location: net/xdp/xdp_umem.c:340
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (c000000000ec11bc)
Location: net/xdp/xdp_umem.c:340
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffe0008ad796)
Location: net/xdp/xdp_umem.c:340
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a4bd7a)
Location: net/xdp/xdp_umem.c:340
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81a0896a)
Location: net/xdp/xdp_umem.c:340
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ab7c2a)
Location: net/xdp/xdp_umem.c:340
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xdp_umem.c (ffffffff81ac404a)
Location: net/xdp/xdp_umem.c:340
Inline: True
Inline callers:
  - net/xdp/xdp_umem.c:xdp_umem_create
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
