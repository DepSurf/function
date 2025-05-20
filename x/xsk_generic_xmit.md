# Function: <code>xsk_generic_xmit</code>

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
In net/xdp/xsk.c (ffffffff819cc15e)
Location: net/xdp/xsk.c:209
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_sendmsg
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
In net/xdp/xsk.c (ffffffff81a05341)
Location: net/xdp/xsk.c:221
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_sendmsg
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
In net/xdp/xsk.c (ffffffff81a7499d)
Location: net/xdp/xsk.c:231
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_sendmsg
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
In net/xdp/xsk.c (ffffffff81aaa40e)
Location: net/xdp/xsk.c:338
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xsk_generic_xmit(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba77d0)
Location: net/xdp/xsk.c:329
Inline: False
```
**Symbols:**

```
ffffffff81ba77d0-ffffffff81ba7afb: xsk_generic_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xsk_generic_xmit(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb6e60)
Location: net/xdp/xsk.c:433
Inline: False
```
**Symbols:**

```
ffffffff81bb6e60-ffffffff81bb7270: xsk_generic_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xsk_generic_xmit(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba5d80)
Location: net/xdp/xsk.c:539
Inline: False
```
**Symbols:**

```
ffffffff81ba5d80-ffffffff81ba6230: xsk_generic_xmit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xsk_generic_xmit(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:539
Inline: False
Direct callers:
  - net/xdp/xsk.c:__xsk_sendmsg
```
**Symbols:**

```
ffffffff81c73700-ffffffff81c73bc7: xsk_generic_xmit (STB_LOCAL)
ffffffff81d43033-ffffffff81d43051: xsk_generic_xmit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xsk_generic_xmit(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:514
Inline: False
Direct callers:
  - net/xdp/xsk.c:xsk_xmit
```
**Symbols:**

```
ffffffff81e17e60-ffffffff81e183bb: xsk_generic_xmit (STB_LOCAL)
ffffffff81f0fa40-ffffffff81f0fa65: xsk_generic_xmit.cold (STB_LOCAL)
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
In net/xdp/xsk.c (ffffffff81fef8f5)
Location: net/xdp/xsk.c:597
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
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
In net/xdp/xsk.c (ffffffff8206b8b5)
Location: net/xdp/xsk.c:598
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
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
In net/xdp/xsk.c (ffffffff8213f5f5)
Location: net/xdp/xsk.c:871
Inline: True
Inline callers:
  - net/xdp/xsk.c:xsk_poll
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
In net/xdp/xsk.c (ffff800010d7e0c4)
Location: net/xdp/xsk.c:338
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
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
In net/xdp/xsk.c (c0e79618)
Location: net/xdp/xsk.c:338
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
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
In net/xdp/xsk.c (c000000000ebea8c)
Location: net/xdp/xsk.c:338
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
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
In net/xdp/xsk.c (ffffffe0008ac550)
Location: net/xdp/xsk.c:338
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
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
In net/xdp/xsk.c (ffffffff81a4979e)
Location: net/xdp/xsk.c:338
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
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
In net/xdp/xsk.c (ffffffff81a0638e)
Location: net/xdp/xsk.c:338
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
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
In net/xdp/xsk.c (ffffffff81ab564e)
Location: net/xdp/xsk.c:338
Inline: True
Inline callers:
  - net/xdp/xsk.c:__xsk_sendmsg
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
In net/xdp/xsk.c (ffffffff81ac2d10)
Location: net/xdp/xsk.c:338
Inline: True
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
</ul>
