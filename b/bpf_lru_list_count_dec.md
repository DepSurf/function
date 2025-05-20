# Function: <code>bpf_lru_list_count_dec</code>

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
In kernel/bpf/bpf_lru_list.c (ffffffff81196151)
Location: kernel/bpf/bpf_lru_list.c:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff8119d6bd)
Location: kernel/bpf/bpf_lru_list.c:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811ad279)
Location: kernel/bpf/bpf_lru_list.c:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811c4849)
Location: kernel/bpf/bpf_lru_list.c:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811d6439)
Location: kernel/bpf/bpf_lru_list.c:57
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811eadb2)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811f7512)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff8121b7f4)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
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
In kernel/bpf/bpf_lru_list.c (ffffffff8121e774)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
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
In kernel/bpf/bpf_lru_list.c (ffffffff8122206b)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
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
In kernel/bpf/bpf_lru_list.c (ffffffff81259c8a)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
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
In kernel/bpf/bpf_lru_list.c (ffffffff812a2caa)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
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
In kernel/bpf/bpf_lru_list.c (ffffffff813007ba)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
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
In kernel/bpf/bpf_lru_list.c (ffffffff8132f323)
Location: kernel/bpf/bpf_lru_list.c:59
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
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
In kernel/bpf/bpf_lru_list.c (ffffffff81353843)
Location: kernel/bpf/bpf_lru_list.c:59
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_list_rotate_active
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
In kernel/bpf/bpf_lru_list.c (ffff80001027c390)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (c04adfe0)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (c000000000325bc8)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (ffffffe0001b3cc0)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811efb32)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811e2882)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811ed902)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
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
In kernel/bpf/bpf_lru_list.c (ffffffff811fbdd2)
Location: kernel/bpf/bpf_lru_list.c:54
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_to_free
```
</details>
</li>
</ul>

## Differences
