# Function: <code>static_key_set_entries</code>

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
In kernel/jump_label.c (ffffffff811b478d)
Location: kernel/jump_label.c:288
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff811c7f20)
Location: kernel/jump_label.c:342
Inline: True
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_init
```
**Symbols:**

```
ffffffff811c7f20-ffffffff811c7f4c: static_key_set_entries.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff811e8470)
Location: kernel/jump_label.c:343
Inline: True
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_init
```
**Symbols:**

```
ffffffff811e8470-ffffffff811e849c: static_key_set_entries.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/jump_label.c (ffffffff811f9130)
Location: kernel/jump_label.c:356
Inline: True
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_init
```
**Symbols:**

```
ffffffff811f9130-ffffffff811f915c: static_key_set_entries.isra.13 (STB_LOCAL)
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
In kernel/jump_label.c (ffffffff81211060)
Location: kernel/jump_label.c:380
Inline: True
Direct callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_init
```
**Symbols:**

```
ffffffff81211060-ffffffff8121108e: static_key_set_entries.isra.0 (STB_LOCAL)
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
In kernel/jump_label.c (ffffffff8121ea9e)
Location: kernel/jump_label.c:380
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void static_key_set_entries(struct static_key *key, struct jump_entry *entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff8124b273)
Location: kernel/jump_label.c:380
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
Direct callers:
  - kernel/jump_label.c:jump_label_init
```
**Symbols:**

```
ffffffff8124a8b0-ffffffff8124a8e2: static_key_set_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void static_key_set_entries(struct static_key *key, struct jump_entry *entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff812556d3)
Location: kernel/jump_label.c:380
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
Direct callers:
  - kernel/jump_label.c:jump_label_init
```
**Symbols:**

```
ffffffff81254c50-ffffffff81254c82: static_key_set_entries (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void static_key_set_entries(struct static_key *key, struct jump_entry *entries);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (ffffffff81259bd3)
Location: kernel/jump_label.c:382
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
Direct callers:
  - kernel/jump_label.c:jump_label_init
```
**Symbols:**

```
ffffffff81259200-ffffffff81259232: static_key_set_entries (STB_LOCAL)
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
In kernel/jump_label.c (ffffffff81295943)
Location: kernel/jump_label.c:382
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
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
In kernel/jump_label.c (ffffffff812eac4a)
Location: kernel/jump_label.c:382
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
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
In kernel/jump_label.c (ffffffff81354bba)
Location: kernel/jump_label.c:406
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
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
In kernel/jump_label.c (ffffffff81385fcb)
Location: kernel/jump_label.c:406
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
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
In kernel/jump_label.c (ffffffff813af48b)
Location: kernel/jump_label.c:406
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_add_module
  - kernel/jump_label.c:jump_label_init
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
In kernel/jump_label.c (ffff8000102aac4c)
Location: kernel/jump_label.c:380
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_init
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/jump_label.c (c00000000035f290)
Location: kernel/jump_label.c:380
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_init
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/jump_label.c (ffffffff812170ee)
Location: kernel/jump_label.c:380
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_init
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
In kernel/jump_label.c (ffffffff81209e4e)
Location: kernel/jump_label.c:380
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_init
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
In kernel/jump_label.c (ffffffff81214e8e)
Location: kernel/jump_label.c:380
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_init
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
In kernel/jump_label.c (ffffffff81223e3e)
Location: kernel/jump_label.c:380
Inline: True
Inline callers:
  - kernel/jump_label.c:jump_label_module_notify
  - kernel/jump_label.c:jump_label_del_module
  - kernel/jump_label.c:jump_label_init
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
