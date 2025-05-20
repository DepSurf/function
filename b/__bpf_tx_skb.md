# Function: <code>__bpf_tx_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179e755)
Location: net/core/filter.c:1591
Inline: True
Inline callers:
  - net/core/filter.c:skb_do_redirect
  - net/core/filter.c:bpf_clone_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cbc0f)
Location: net/core/filter.c:1649
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ea6c2)
Location: net/core/filter.c:1675
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81865df2)
Location: net/core/filter.c:1696
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b3f85)
Location: net/core/filter.c:1982
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff818dc771)
Location: net/core/filter.c:2001
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff819298a2)
Location: net/core/filter.c:2047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff8195bf0b)
Location: net/core/filter.c:2047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff81a31101)
Location: net/core/filter.c:2072
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/filter.c (ffffffff81a33591)
Location: net/core/filter.c:2102
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/filter.c (ffffffff81a1a33a)
Location: net/core/filter.c:2099
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/filter.c (ffffffff81acc59f)
Location: net/core/filter.c:2100
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/filter.c (ffffffff81c4926a)
Location: net/core/filter.c:2101
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/filter.c (ffffffff81dfdc59)
Location: net/core/filter.c:2103
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/filter.c (ffffffff81e6f1b7)
Location: net/core/filter.c:2114
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/filter.c (ffffffff81f2e7f7)
Location: net/core/filter.c:2121
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect_no_mac
  - net/core/filter.c:__bpf_redirect_no_mac
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
In net/core/filter.c (ffff800010c01438)
Location: net/core/filter.c:2047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (c0d18548)
Location: net/core/filter.c:2047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (c000000000ce8eb0)
Location: net/core/filter.c:2047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffe00077ff04)
Location: net/core/filter.c:2047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff818fbedb)
Location: net/core/filter.c:2047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff818b5d0b)
Location: net/core/filter.c:2047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff8194cf0b)
Location: net/core/filter.c:2047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
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
In net/core/filter.c (ffffffff8196e8cb)
Location: net/core/filter.c:2047
Inline: True
Inline callers:
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
  - net/core/filter.c:__bpf_redirect
```
</details>
</li>
</ul>

## Differences
