# Function: <code>bpf_common_lru_push_free</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81196abf)
Location: kernel/bpf/bpf_lru_list.c:505
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff8119df1f)
Location: kernel/bpf/bpf_lru_list.c:505
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811adb2f)
Location: kernel/bpf/bpf_lru_list.c:505
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811c50f4)
Location: kernel/bpf/bpf_lru_list.c:505
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811d6cf4)
Location: kernel/bpf/bpf_lru_list.c:505
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811eb6e6)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811f7e46)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_common_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121b390)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
```
**Symbols:**

```
ffffffff8121b390-ffffffff8121b485: bpf_common_lru_push_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_common_lru_push_free(struct bpf_lru *lru, struct bpf_lru_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121e310)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
```
**Symbols:**

```
ffffffff8121e310-ffffffff8121e403: bpf_common_lru_push_free (STB_LOCAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff812225c6)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff8125a261)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff812a32fc)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff81300e5c)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff8132f9bc)
Location: kernel/bpf/bpf_lru_list.c:507
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff81353edc)
Location: kernel/bpf/bpf_lru_list.c:507
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffff80001027cf28)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (c04ae93c)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (c0000000003269c0)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffe0001b44c8)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811f0466)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811e31b6)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811ee236)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811fc706)
Location: kernel/bpf/bpf_lru_list.c:502
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
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
