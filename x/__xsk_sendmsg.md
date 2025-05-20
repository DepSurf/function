# Function: <code>__xsk_sendmsg</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __xsk_sendmsg(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aaa370)
Location: net/xdp/xsk.c:404
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_poll
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81aaa370-ffffffff81aaa703: __xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __xsk_sendmsg(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba7b00)
Location: net/xdp/xsk.c:398
Inline: True
Direct callers:
  - net/xdp/xsk.c:xsk_poll
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81ba7b00-ffffffff81ba7b64: __xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __xsk_sendmsg(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb75d0)
Location: net/xdp/xsk.c:521
Inline: True
Direct callers:
  - net/xdp/xsk.c:xsk_poll
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81bb75d0-ffffffff81bb765a: __xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __xsk_sendmsg(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba67a0)
Location: net/xdp/xsk.c:614
Inline: True
Direct callers:
  - net/xdp/xsk.c:xsk_poll
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81ba67a0-ffffffff81ba682a: __xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __xsk_sendmsg(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:614
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_poll
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81c74400-ffffffff81c744a0: __xsk_sendmsg (STB_LOCAL)
ffffffff81d430c3-ffffffff81d430d7: __xsk_sendmsg.cold (STB_LOCAL)
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
In net/xdp/xsk.c (ffffffff81e185eb)
Location: net/xdp/xsk.c:630
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_sendmsg
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
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:631
Inline: True
Direct callers:
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81fef580-ffffffff81fef788: __xsk_sendmsg.constprop.0.isra.0 (STB_LOCAL)
ffffffff820b5dfb-ffffffff820b5e3a: __xsk_sendmsg.constprop.0.isra.0.cold (STB_LOCAL)
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
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:632
Inline: True
Direct callers:
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff8206b540-ffffffff8206b748: __xsk_sendmsg.isra.0 (STB_LOCAL)
ffffffff8213732f-ffffffff8213736e: __xsk_sendmsg.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:905
Inline: True
Direct callers:
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff8213f2d0-ffffffff8213f4d5: __xsk_sendmsg.isra.0 (STB_LOCAL)
ffffffff822191da-ffffffff82219219: __xsk_sendmsg.isra.0.cold (STB_LOCAL)
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
int __xsk_sendmsg(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d7e040)
Location: net/xdp/xsk.c:404
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_poll
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffff800010d7e040-ffff800010d7e3b8: __xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __xsk_sendmsg(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e79588)
Location: net/xdp/xsk.c:404
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_poll
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
c0e79588-c0e799d8: __xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __xsk_sendmsg(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ebe9d0)
Location: net/xdp/xsk.c:404
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_poll
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
c000000000ebe9d0-c000000000ebeea8: __xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __xsk_sendmsg(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008ac4da)
Location: net/xdp/xsk.c:404
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_poll
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffe0008ac4da-ffffffe0008ac79e: __xsk_sendmsg (STB_LOCAL)
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
int __xsk_sendmsg(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a49700)
Location: net/xdp/xsk.c:404
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_poll
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81a49700-ffffffff81a49a93: __xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __xsk_sendmsg(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a062f0)
Location: net/xdp/xsk.c:404
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_poll
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81a062f0-ffffffff81a06683: __xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __xsk_sendmsg(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab55b0)
Location: net/xdp/xsk.c:404
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_poll
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81ab55b0-ffffffff81ab5943: __xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __xsk_sendmsg(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac2cb0)
Location: net/xdp/xsk.c:404
Inline: True
Direct callers:
  - net/xdp/xsk.c:xsk_poll
  - net/xdp/xsk.c:xsk_sendmsg
```
**Symbols:**

```
ffffffff81ac2cb0-ffffffff81ac3046: __xsk_sendmsg (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
