# Function: <code>xsk_unbind_dev</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xsk_unbind_dev(struct xdp_sock *xs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a73ae0)
Location: net/xdp/xsk.c:349
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81a73ae0-ffffffff81a73b42: xsk_unbind_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xsk_unbind_dev(struct xdp_sock *xs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aaa1f0)
Location: net/xdp/xsk.c:477
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81aaa1f0-ffffffff81aaa249: xsk_unbind_dev (STB_LOCAL)
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
In net/xdp/xsk.c (ffffffff81ba657e)
Location: net/xdp/xsk.c:471
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
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
In net/xdp/xsk.c (ffffffff81bb6dde)
Location: net/xdp/xsk.c:643
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
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
In net/xdp/xsk.c (ffffffff81ba5cfe)
Location: net/xdp/xsk.c:736
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
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
In net/xdp/xsk.c (ffffffff81c74358)
Location: net/xdp/xsk.c:736
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
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
In net/xdp/xsk.c (ffffffff81e1739c)
Location: net/xdp/xsk.c:755
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
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
In net/xdp/xsk.c (ffffffff81fede1e)
Location: net/xdp/xsk.c:765
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
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
In net/xdp/xsk.c (ffffffff82069f7e)
Location: net/xdp/xsk.c:766
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
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
In net/xdp/xsk.c (ffffffff8213d3de)
Location: net/xdp/xsk.c:1038
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
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
void xsk_unbind_dev(struct xdp_sock *xs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d7ecc0)
Location: net/xdp/xsk.c:477
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffff800010d7ecc0-ffff800010d7ed3c: xsk_unbind_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void xsk_unbind_dev(struct xdp_sock *xs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e788c4)
Location: net/xdp/xsk.c:477
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
c0e788c4-c0e78930: xsk_unbind_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void xsk_unbind_dev(struct xdp_sock *xs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ebf080)
Location: net/xdp/xsk.c:477
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
c000000000ebf080-c000000000ebf120: xsk_unbind_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xsk_unbind_dev(struct xdp_sock *xs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008ab538)
Location: net/xdp/xsk.c:477
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffe0008ab538-ffffffe0008ab5c0: xsk_unbind_dev (STB_LOCAL)
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
void xsk_unbind_dev(struct xdp_sock *xs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a49580)
Location: net/xdp/xsk.c:477
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81a49580-ffffffff81a495d9: xsk_unbind_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void xsk_unbind_dev(struct xdp_sock *xs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a06170)
Location: net/xdp/xsk.c:477
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81a06170-ffffffff81a061c9: xsk_unbind_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xsk_unbind_dev(struct xdp_sock *xs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab5430)
Location: net/xdp/xsk.c:477
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81ab5430-ffffffff81ab5489: xsk_unbind_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xsk_unbind_dev(struct xdp_sock *xs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac1a20)
Location: net/xdp/xsk.c:477
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_notifier
  - net/xdp/xsk.c:xsk_release
```
**Symbols:**

```
ffffffff81ac1a20-ffffffff81ac1a79: xsk_unbind_dev (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
