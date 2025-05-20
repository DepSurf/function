# Function: <code>__xsk_rcv</code>

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
In net/xdp/xsk.c (ffffffff819cc645)
Location: net/xdp/xsk.c:56
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81a056b8)
Location: net/xdp/xsk.c:56
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81a74fcb)
Location: net/xdp/xsk.c:58
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81aabc92)
Location: net/xdp/xsk.c:141
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp, u32 len, bool explicit_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba74a0)
Location: net/xdp/xsk.c:152
Inline: False
```
**Symbols:**

```
ffffffff81ba74a0-ffffffff81ba7577: __xsk_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp, u32 len, bool explicit_free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb6c00)
Location: net/xdp/xsk.c:187
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
```
**Symbols:**

```
ffffffff81bb6c00-ffffffff81bb6cd8: __xsk_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba5bb0)
Location: net/xdp/xsk.c:187
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff81ba5bb0-ffffffff81ba5c72: __xsk_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81c73630)
Location: net/xdp/xsk.c:187
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff81c73630-ffffffff81c736f2: __xsk_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81e17230)
Location: net/xdp/xsk.c:172
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff81e17230-ffffffff81e1731c: __xsk_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81fee090)
Location: net/xdp/xsk.c:172
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff81fee090-ffffffff81fee15f: __xsk_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8206a1f0)
Location: net/xdp/xsk.c:173
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff8206a1f0-ffffffff8206a2bf: __xsk_rcv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __xsk_rcv(struct xdp_sock *xs, struct xdp_buff *xdp, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8213d6c0)
Location: net/xdp/xsk.c:228
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_map_redirect
  - net/xdp/xsk.c:xsk_generic_rcv
```
**Symbols:**

```
ffffffff8213d6c0-ffffffff8213d96a: __xsk_rcv (STB_LOCAL)
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
In net/xdp/xsk.c (ffff800010d803b8)
Location: net/xdp/xsk.c:141
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (c0e7a794)
Location: net/xdp/xsk.c:141
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (c000000000ebff50)
Location: net/xdp/xsk.c:141
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffe0008acc54)
Location: net/xdp/xsk.c:141
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81a4b022)
Location: net/xdp/xsk.c:141
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81a07c12)
Location: net/xdp/xsk.c:141
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81ab6ed2)
Location: net/xdp/xsk.c:141
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
In net/xdp/xsk.c (ffffffff81ac32f2)
Location: net/xdp/xsk.c:141
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_rcv
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>u32 len</code>
</li>
<li>
<b>Param removed. </b>
<code>bool explicit_free</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 len</code>
</li>
</ul>
</details>
</li>
</ul>
