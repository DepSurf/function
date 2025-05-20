# Function: <code>__ftrace_lookup_ip</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8115a6fa)
Location: kernel/trace/ftrace.c:1214
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff8116738a)
Location: kernel/trace/ftrace.c:1190
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff8117627a)
Location: kernel/trace/ftrace.c:1179
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff81183eba)
Location: kernel/trace/ftrace.c:1128
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff81190c30)
Location: kernel/trace/ftrace.c:1125
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff8119cc30)
Location: kernel/trace/ftrace.c:1126
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff811aebf4)
Location: kernel/trace/ftrace.c:1114
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:find_direct_entry
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff811ac4e3)
Location: kernel/trace/ftrace.c:1113
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:find_direct_entry
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff811ad052)
Location: kernel/trace/ftrace.c:1113
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:find_direct_entry
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff811d6ce4)
Location: kernel/trace/ftrace.c:1114
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:find_direct_entry
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff8120c079)
Location: kernel/trace/ftrace.c:1108
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:referenced_filters
  - kernel/trace/ftrace.c:modify_ftrace_direct_multi
  - kernel/trace/ftrace.c:remove_direct_functions_hash
  - kernel/trace/ftrace.c:find_direct_entry
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff81254b17)
Location: kernel/trace/ftrace.c:1108
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:remove_direct_functions_hash
  - kernel/trace/ftrace.c:find_direct_entry
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff8126be37)
Location: kernel/trace/ftrace.c:1139
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:remove_direct_functions_hash
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff81286427)
Location: kernel/trace/ftrace.c:1139
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ops_references_ip
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:ftrace_find_rec_direct
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffff800010215a48)
Location: kernel/trace/ftrace.c:1126
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (c04547e0)
Location: kernel/trace/ftrace.c:1126
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (c0000000002974c8)
Location: kernel/trace/ftrace.c:1126
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffe0001756f2)
Location: kernel/trace/ftrace.c:1126
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:hash_contains_ip
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff81195250)
Location: kernel/trace/ftrace.c:1126
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff81188360)
Location: kernel/trace/ftrace.c:1126
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff81193020)
Location: kernel/trace/ftrace.c:1126
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_lookup_ip
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
In kernel/trace/ftrace.c (ffffffff811a0bb0)
Location: kernel/trace/ftrace.c:1126
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_module_enable
  - kernel/trace/ftrace.c:ftrace_lookup_ip
```
</details>
</li>
</ul>

## Differences
