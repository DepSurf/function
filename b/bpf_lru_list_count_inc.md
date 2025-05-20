# Function: <code>bpf_lru_list_count_inc</code>

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
In kernel/bpf/bpf_lru_list.c (ffffffff81196156)
Location: kernel/bpf/bpf_lru_list.c:50
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (ffffffff8119d6c3)
Location: kernel/bpf/bpf_lru_list.c:50
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (ffffffff811ad27f)
Location: kernel/bpf/bpf_lru_list.c:50
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (ffffffff811c484f)
Location: kernel/bpf/bpf_lru_list.c:50
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (ffffffff811d643f)
Location: kernel/bpf/bpf_lru_list.c:50
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (ffffffff811eadb8)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (ffffffff811f7518)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (ffffffff8121b700)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__local_list_flush
  - kernel/bpf/bpf_lru_list.c:__local_list_flush
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
In kernel/bpf/bpf_lru_list.c (ffffffff8121e680)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__local_list_flush
  - kernel/bpf/bpf_lru_list.c:__local_list_flush
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
In kernel/bpf/bpf_lru_list.c (ffffffff81221f99)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff81259b73)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff812a2be5)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff813006f5)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff8132f203)
Location: kernel/bpf/bpf_lru_list.c:52
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffffffff81353723)
Location: kernel/bpf/bpf_lru_list.c:52
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
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
In kernel/bpf/bpf_lru_list.c (ffff80001027c398)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (c04adff4)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (c000000000325bd0)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (ffffffe0001b3cc6)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (ffffffff811efb38)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (ffffffff811e2888)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (ffffffff811ed908)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
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
In kernel/bpf/bpf_lru_list.c (ffffffff811fbdd8)
Location: kernel/bpf/bpf_lru_list.c:47
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move
  - kernel/bpf/bpf_lru_list.c:__bpf_lru_node_move_in
```
</details>
</li>
</ul>

## Differences
