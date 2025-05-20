# Function: <code>reuseport_grow</code>

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
In net/core/sock_reuseport.c (ffffffff817a03bc)
Location: net/core/sock_reuseport.c:58
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff817ced8c)
Location: net/core/sock_reuseport.c:58
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff817ee134)
Location: net/core/sock_reuseport.c:58
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff8186a384)
Location: net/core/sock_reuseport.c:65
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff818ba0ad)
Location: net/core/sock_reuseport.c:65
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff818e0ed0)
Location: net/core/sock_reuseport.c:97
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff8192f6a6)
Location: net/core/sock_reuseport.c:97
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff81961916)
Location: net/core/sock_reuseport.c:97
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff81a34f32)
Location: net/core/sock_reuseport.c:87
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff81a37272)
Location: net/core/sock_reuseport.c:87
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff81a1e3d2)
Location: net/core/sock_reuseport.c:87
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sock_reuseport *reuseport_grow(struct sock_reuseport *reuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81ad1f50)
Location: net/core/sock_reuseport.c:162
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_add_sock
```
**Symbols:**

```
ffffffff81ad1f50-ffffffff81ad2110: reuseport_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sock_reuseport *reuseport_grow(struct sock_reuseport *reuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81c4f950)
Location: net/core/sock_reuseport.c:162
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_add_sock
```
**Symbols:**

```
ffffffff81c4f950-ffffffff81c4fb02: reuseport_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sock_reuseport *reuseport_grow(struct sock_reuseport *reuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e04810)
Location: net/core/sock_reuseport.c:247
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_add_sock
```
**Symbols:**

```
ffffffff81e04810-ffffffff81e0498f: reuseport_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sock_reuseport *reuseport_grow(struct sock_reuseport *reuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81e77060)
Location: net/core/sock_reuseport.c:247
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_add_sock
```
**Symbols:**

```
ffffffff81e77060-ffffffff81e771e0: reuseport_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sock_reuseport *reuseport_grow(struct sock_reuseport *reuse);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_reuseport.c (ffffffff81f37020)
Location: net/core/sock_reuseport.c:247
Inline: False
Direct callers:
  - net/core/sock_reuseport.c:reuseport_resurrect
  - net/core/sock_reuseport.c:reuseport_add_sock
```
**Symbols:**

```
ffffffff81f37020-ffffffff81f371a0: reuseport_grow (STB_LOCAL)
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
In net/core/sock_reuseport.c (ffff800010c054b8)
Location: net/core/sock_reuseport.c:97
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (c0d1e6c4)
Location: net/core/sock_reuseport.c:97
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (c000000000cef650)
Location: net/core/sock_reuseport.c:97
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffe000783dac)
Location: net/core/sock_reuseport.c:97
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff819018e6)
Location: net/core/sock_reuseport.c:97
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff818bb716)
Location: net/core/sock_reuseport.c:97
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff81952916)
Location: net/core/sock_reuseport.c:97
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
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
In net/core/sock_reuseport.c (ffffffff81974386)
Location: net/core/sock_reuseport.c:97
Inline: True
Inline callers:
  - net/core/sock_reuseport.c:reuseport_add_sock
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
