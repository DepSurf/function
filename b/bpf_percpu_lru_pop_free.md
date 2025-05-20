# Function: <code>bpf_percpu_lru_pop_free</code>

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
In kernel/bpf/bpf_lru_list.c (ffffffff8119663c)
Location: kernel/bpf/bpf_lru_list.c:402
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff8119da1c)
Location: kernel/bpf/bpf_lru_list.c:402
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811ad7fd)
Location: kernel/bpf/bpf_lru_list.c:402
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811c4b79)
Location: kernel/bpf/bpf_lru_list.c:402
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811d6769)
Location: kernel/bpf/bpf_lru_list.c:402
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811eb599)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811f7cf9)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_percpu_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121b5e0)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff8121b5e0-ffffffff8121b6c4: bpf_percpu_lru_pop_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_lru_node *bpf_percpu_lru_pop_free(struct bpf_lru *lru, u32 hash);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121e560)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff8121e560-ffffffff8121e644: bpf_percpu_lru_pop_free (STB_LOCAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff81222479)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff8125a0d8)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff812a3155)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff81300ca5)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff8132f805)
Location: kernel/bpf/bpf_lru_list.c:404
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff81353d25)
Location: kernel/bpf/bpf_lru_list.c:404
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffff80001027c7e0)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (c04ae7dc)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (c0000000003267d4)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffe0001b43aa)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811f0319)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811e3069)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811ee0e9)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811fc5b9)
Location: kernel/bpf/bpf_lru_list.c:399
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
