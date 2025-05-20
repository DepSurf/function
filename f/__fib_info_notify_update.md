# Function: <code>__fib_info_notify_update</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff819ce14d)
Location: net/ipv4/fib_trie.c:1948
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (ffffffff81a04cac)
Location: net/ipv4/fib_trie.c:1948
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __fib_info_notify_update(struct net *net, struct fib_table *tb, struct nl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81af1f50)
Location: net/ipv4/fib_trie.c:2059
Inline: False
Direct callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
```
**Symbols:**

```
ffffffff81af1f50-ffffffff81af20c8: __fib_info_notify_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_trie.c (ffffffff81afe660)
Location: net/ipv4/fib_trie.c:2059
Inline: True
Direct callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
```
**Symbols:**

```
ffffffff81afe660-ffffffff81afe73d: __fib_info_notify_update.constprop.0 (STB_LOCAL)
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
In net/ipv4/fib_trie.c (ffffffff81aecb9c)
Location: net/ipv4/fib_trie.c:2096
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (ffffffff81bacf4f)
Location: net/ipv4/fib_trie.c:2100
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (ffffffff81d3fe80)
Location: net/ipv4/fib_trie.c:2109
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (ffffffff81f08ac0)
Location: net/ipv4/fib_trie.c:2111
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (ffffffff81f685d0)
Location: net/ipv4/fib_trie.c:2111
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (ffffffff8202ec50)
Location: net/ipv4/fib_trie.c:2117
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (ffff800010cbd880)
Location: net/ipv4/fib_trie.c:1948
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (c0dc922c)
Location: net/ipv4/fib_trie.c:1948
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (c000000000dd7ae8)
Location: net/ipv4/fib_trie.c:1948
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (ffffffe000813b0e)
Location: net/ipv4/fib_trie.c:1948
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (ffffffff819a4a4c)
Location: net/ipv4/fib_trie.c:1948
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (ffffffff8195e50c)
Location: net/ipv4/fib_trie.c:1948
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (ffffffff81a0f2ec)
Location: net/ipv4/fib_trie.c:1948
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
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
In net/ipv4/fib_trie.c (ffffffff81a19b3c)
Location: net/ipv4/fib_trie.c:1948
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_info_notify_update
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
