# Function: <code>bpf_timer_cancel_and_free</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_timer_cancel_and_free(void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81250be0)
Location: kernel/bpf/helpers.c:1290
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_batch
  - kernel/bpf/hashtab.c:__htab_map_lookup_and_delete_elem
  - kernel/bpf/hashtab.c:htab_map_free
  - kernel/bpf/hashtab.c:htab_lru_map_delete_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_lru_map_update_elem
  - kernel/bpf/hashtab.c:htab_map_update_elem
  - kernel/bpf/hashtab.c:htab_elem_free_rcu
  - kernel/bpf/hashtab.c:htab_lru_map_delete_node
  - kernel/bpf/arraymap.c:array_map_update_elem
```
**Symbols:**

```
ffffffff81250be0-ffffffff81250c71: bpf_timer_cancel_and_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_timer_cancel_and_free(void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81298330)
Location: kernel/bpf/helpers.c:1349
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_free_timers
  - kernel/bpf/hashtab.c:htab_map_free_timers
  - kernel/bpf/hashtab.c:check_and_free_fields
  - kernel/bpf/arraymap.c:array_map_update_elem
```
**Symbols:**

```
ffffffff81298330-ffffffff812983dd: bpf_timer_cancel_and_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_timer_cancel_and_free(void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff812f34f0)
Location: kernel/bpf/helpers.c:1334
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_free_fields
  - kernel/bpf/syscall.c:bpf_obj_free_timer
```
**Symbols:**

```
ffffffff812f34f0-ffffffff812f359d: bpf_timer_cancel_and_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_timer_cancel_and_free(void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81320380)
Location: kernel/bpf/helpers.c:1353
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_free_fields
  - kernel/bpf/syscall.c:bpf_obj_free_timer
```
**Symbols:**

```
ffffffff81320380-ffffffff8132042d: bpf_timer_cancel_and_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_timer_cancel_and_free(void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/helpers.c (ffffffff81342870)
Location: kernel/bpf/helpers.c:1372
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_obj_free_fields
  - kernel/bpf/syscall.c:bpf_obj_free_timer
```
**Symbols:**

```
ffffffff81342870-ffffffff81342928: bpf_timer_cancel_and_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
