# Function: <code>local_free_list</code>

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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:34
Inline: True
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:34
Inline: True
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
In kernel/bpf/bpf_lru_list.c (0)
Location: kernel/bpf/bpf_lru_list.c:34
Inline: True
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
In kernel/bpf/bpf_lru_list.c (ffffffff811c5148)
Location: kernel/bpf/bpf_lru_list.c:34
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811d6d48)
Location: kernel/bpf/bpf_lru_list.c:34
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811eb73e)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811f7e9e)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff8121b439)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff8121e3bd)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff81222626)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff8125a2d2)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff812a3366)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff81300ec6)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff8132fa27)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff81353f47)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffff80001027cff8)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (c04ae9f4)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (c000000000326a78)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffe0001b4564)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811f04be)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811e320e)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811ee28e)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811fc75e)
Location: kernel/bpf/bpf_lru_list.c:31
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_push_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
</details>
</li>
</ul>

## Differences
