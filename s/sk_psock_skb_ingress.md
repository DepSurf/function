# Function: <code>sk_psock_skb_ingress</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e63de)
Location: net/core/skmsg.c:381
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81935d59)
Location: net/core/skmsg.c:390
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81968a79)
Location: net/core/skmsg.c:399
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sk_psock_skb_ingress(struct sk_psock *psock, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3bc20)
Location: net/core/skmsg.c:400
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_backlog
```
**Symbols:**

```
ffffffff81a3bc20-ffffffff81a3bdab: sk_psock_skb_ingress (STB_LOCAL)
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
In net/core/skmsg.c (ffffffff81a3f807)
Location: net/core/skmsg.c:454
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81a4e9d8)
Location: net/core/skmsg.c:550
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81b07547)
Location: net/core/skmsg.c:543
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81c8ccb5)
Location: net/core/skmsg.c:556
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81e47b4d)
Location: net/core/skmsg.c:563
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81ea32cb)
Location: net/core/skmsg.c:562
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81f65606)
Location: net/core/skmsg.c:562
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffff800010c0f8e0)
Location: net/core/skmsg.c:399
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (c0d26220)
Location: net/core/skmsg.c:399
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (c000000000cfa700)
Location: net/core/skmsg.c:399
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffe00078b402)
Location: net/core/skmsg.c:399
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81908a49)
Location: net/core/skmsg.c:399
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff818c2859)
Location: net/core/skmsg.c:399
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff81959a79)
Location: net/core/skmsg.c:399
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
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
In net/core/skmsg.c (ffffffff8197bc99)
Location: net/core/skmsg.c:399
Inline: True
Inline callers:
  - net/core/skmsg.c:sk_psock_backlog
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
