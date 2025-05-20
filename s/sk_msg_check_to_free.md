# Function: <code>sk_msg_check_to_free</code>

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
In net/core/skmsg.c (ffffffff818e6d4a)
Location: include/linux/skmsg.h:127
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/core/skmsg.c (ffffffff819366df)
Location: include/linux/skmsg.h:127
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
Direct callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
```
**Symbols:**

```
ffffffff81937023-ffffffff81937037: sk_msg_check_to_free.isra.0.part.0 (STB_LOCAL)
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
In net/core/skmsg.c (ffffffff819696af)
Location: include/linux/skmsg.h:130
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffffffff81a3d0df)
Location: include/linux/skmsg.h:131
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffffffff81a3fa5f)
Location: include/linux/skmsg.h:131
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffffffff81a4dfd8)
Location: include/linux/skmsg.h:134
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffffffff81b06a28)
Location: include/linux/skmsg.h:133
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffffffff81c8d2b2)
Location: include/linux/skmsg.h:132
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffffffff81e47562)
Location: include/linux/skmsg.h:134
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffffffff81ea35c2)
Location: include/linux/skmsg.h:134
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffffffff81f65c52)
Location: include/linux/skmsg.h:140
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffff800010c0e9a8)
Location: include/linux/skmsg.h:130
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (c0d27694)
Location: include/linux/skmsg.h:130
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (c000000000cfb7c4)
Location: include/linux/skmsg.h:130
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffffffe00078bc9a)
Location: include/linux/skmsg.h:130
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffffffff8190967f)
Location: include/linux/skmsg.h:130
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffffffff818c348f)
Location: include/linux/skmsg.h:130
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffffffff8195a6af)
Location: include/linux/skmsg.h:130
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
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
In net/core/skmsg.c (ffffffff8197c8cf)
Location: include/linux/skmsg.h:130
Inline: True
Inline callers:
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free_partial
  - net/core/skmsg.c:__sk_msg_free
  - net/core/skmsg.c:__sk_msg_free
```
</details>
</li>
</ul>

## Differences
