# Function: <code>xsk_copy_xdp</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba74f1)
Location: net/xdp/xsk.c:134
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv
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
In net/xdp/xsk.c (ffffffff81bb6c52)
Location: net/xdp/xsk.c:169
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv
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
In net/xdp/xsk.c (ffffffff81ba5c06)
Location: net/xdp/xsk.c:169
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv
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
In net/xdp/xsk.c (ffffffff81c73686)
Location: net/xdp/xsk.c:169
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv
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
In net/xdp/xsk.c (ffffffff81e1728e)
Location: net/xdp/xsk.c:154
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_rcv
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (ffffffff81fede90)
Location: net/xdp/xsk.c:154
Inline: True
Direct callers:
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff81fede90-ffffffff81fedec5: xsk_copy_xdp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (ffffffff82069ff0)
Location: net/xdp/xsk.c:155
Inline: True
Direct callers:
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff82069ff0-ffffffff8206a025: xsk_copy_xdp.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 xsk_copy_xdp(void *to, void **from, u32 to_len, u32 *from_len, skb_frag_t **frag, u32 rem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8213c6e0)
Location: net/xdp/xsk.c:200
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_rcv
```
**Symbols:**

```
ffffffff8213c6e0-ffffffff8213c7c1: xsk_copy_xdp (STB_LOCAL)
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
</ul>
