# Function: <code>xsk_init_queue</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int xsk_init_queue(u32 entries, struct xsk_queue **queue, bool umem_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff819cb8b0)
Location: net/xdp/xsk.c:312
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff819cb8b0-ffffffff819cb8f4: xsk_init_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xsk_init_queue(u32 entries, struct xsk_queue **queue, bool umem_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a04b00)
Location: net/xdp/xsk.c:324
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff81a04b00-ffffffff81a04b44: xsk_init_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xsk_init_queue(u32 entries, struct xsk_queue **queue, bool umem_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a73fa0)
Location: net/xdp/xsk.c:331
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff81a73fa0-ffffffff81a73fec: xsk_init_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xsk_init_queue(u32 entries, struct xsk_queue **queue, bool umem_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aaab80)
Location: net/xdp/xsk.c:459
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff81aaab80-ffffffff81aaabcc: xsk_init_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba7e98)
Location: net/xdp/xsk.c:453
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb7adf)
Location: net/xdp/xsk.c:625
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba6c5f)
Location: net/xdp/xsk.c:718
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81c747cf)
Location: net/xdp/xsk.c:718
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81e1895a)
Location: net/xdp/xsk.c:737
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81fefbba)
Location: net/xdp/xsk.c:747
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8206bd5a)
Location: net/xdp/xsk.c:748
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8213f92a)
Location: net/xdp/xsk.c:1020
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int xsk_init_queue(u32 entries, struct xsk_queue **queue, bool umem_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d7e420)
Location: net/xdp/xsk.c:459
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffff800010d7e420-ffff800010d7e4ac: xsk_init_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xsk_init_queue(u32 entries, struct xsk_queue **queue, bool umem_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e78c6c)
Location: net/xdp/xsk.c:459
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
c0e78c6c-c0e78cd4: xsk_init_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xsk_init_queue(u32 entries, struct xsk_queue **queue, bool umem_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ebdd50)
Location: net/xdp/xsk.c:459
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
c000000000ebdd50-c000000000ebddf8: xsk_init_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xsk_init_queue(u32 entries, struct xsk_queue **queue, bool umem_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008abae6)
Location: net/xdp/xsk.c:459
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffe0008abae6-ffffffe0008abb56: xsk_init_queue (STB_LOCAL)
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
int xsk_init_queue(u32 entries, struct xsk_queue **queue, bool umem_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a49f10)
Location: net/xdp/xsk.c:459
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff81a49f10-ffffffff81a49f5c: xsk_init_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xsk_init_queue(u32 entries, struct xsk_queue **queue, bool umem_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a06b00)
Location: net/xdp/xsk.c:459
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff81a06b00-ffffffff81a06b4c: xsk_init_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xsk_init_queue(u32 entries, struct xsk_queue **queue, bool umem_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab5dc0)
Location: net/xdp/xsk.c:459
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff81ab5dc0-ffffffff81ab5e0c: xsk_init_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xsk_init_queue(u32 entries, struct xsk_queue **queue, bool umem_queue);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac1fd0)
Location: net/xdp/xsk.c:459
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
  - net/xdp/xsk.c:xsk_setsockopt
```
**Symbols:**

```
ffffffff81ac1fd0-ffffffff81ac201c: xsk_init_queue (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
