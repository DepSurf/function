# Function: <code>fib_find_info_nh</code>

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
In net/ipv4/fib_semantics.c (ffffffff819c9316)
Location: net/ipv4/fib_semantics.c:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff819ffecf)
Location: net/ipv4/fib_semantics.c:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fib_info *fib_find_info_nh(struct net *net, const struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aec820)
Location: net/ipv4/fib_semantics.c:367
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81aec820-ffffffff81aec8dc: fib_find_info_nh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fib_info *fib_find_info_nh(struct net *net, const struct fib_config *cfg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81af9700)
Location: net/ipv4/fib_semantics.c:367
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81af9700-ffffffff81af97bc: fib_find_info_nh (STB_LOCAL)
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
In net/ipv4/fib_semantics.c (ffffffff81ae794c)
Location: net/ipv4/fib_semantics.c:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff81ba7633)
Location: net/ipv4/fib_semantics.c:373
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff81d3a10a)
Location: net/ipv4/fib_semantics.c:375
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff81f02a6a)
Location: net/ipv4/fib_semantics.c:376
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff81f625c1)
Location: net/ipv4/fib_semantics.c:376
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff82028b91)
Location: net/ipv4/fib_semantics.c:377
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffff800010cb8674)
Location: net/ipv4/fib_semantics.c:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (c0dc389c)
Location: net/ipv4/fib_semantics.c:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (c000000000dd0e80)
Location: net/ipv4/fib_semantics.c:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffe00080f5a0)
Location: net/ipv4/fib_semantics.c:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff8199fc6f)
Location: net/ipv4/fib_semantics.c:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff8195972f)
Location: net/ipv4/fib_semantics.c:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff81a0a50f)
Location: net/ipv4/fib_semantics.c:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
In net/ipv4/fib_semantics.c (ffffffff81a14cef)
Location: net/ipv4/fib_semantics.c:367
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
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
</ul>
