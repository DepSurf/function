# Function: <code>ext4_free_data_in_buddy</code>

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
In fs/ext4/mballoc.c (ffffffff813103e3)
Location: fs/ext4/mballoc.c:2807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813352c3)
Location: fs/ext4/mballoc.c:2807
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff81363631)
Location: fs/ext4/mballoc.c:2776
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff8137b841)
Location: fs/ext4/mballoc.c:2776
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813a58e6)
Location: fs/ext4/mballoc.c:2778
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813be766)
Location: fs/ext4/mballoc.c:2796
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_free_data_in_buddy(struct super_block *sb, struct ext4_free_data *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814068b0)
Location: fs/ext4/mballoc.c:2919
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
**Symbols:**

```
ffffffff814068b0-ffffffff81406bc5: ext4_free_data_in_buddy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_free_data_in_buddy(struct super_block *sb, struct ext4_free_data *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff814196e0)
Location: fs/ext4/mballoc.c:3023
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
**Symbols:**

```
ffffffff814196e0-ffffffff814199e9: ext4_free_data_in_buddy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_free_data_in_buddy(struct super_block *sb, struct ext4_free_data *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141fea0)
Location: fs/ext4/mballoc.c:3555
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
```
**Symbols:**

```
ffffffff8141fea0-ffffffff8142010a: ext4_free_data_in_buddy (STB_LOCAL)
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
In fs/ext4/mballoc.c (ffffffff81477801)
Location: fs/ext4/mballoc.c:3637
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff814f9b4e)
Location: fs/ext4/mballoc.c:3634
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff8159436e)
Location: fs/ext4/mballoc.c:3604
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff815cb358)
Location: fs/ext4/mballoc.c:3827
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff816040fa)
Location: fs/ext4/mballoc.c:3851
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffff8000104952c8)
Location: fs/ext4/mballoc.c:2796
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (c0656f3c)
Location: fs/ext4/mballoc.c:2796
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (c0000000005bec14)
Location: fs/ext4/mballoc.c:2796
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffe000319f06)
Location: fs/ext4/mballoc.c:2796
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813b6d46)
Location: fs/ext4/mballoc.c:2796
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813a77d6)
Location: fs/ext4/mballoc.c:2796
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813b45a6)
Location: fs/ext4/mballoc.c:2796
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
In fs/ext4/mballoc.c (ffffffff813c91b1)
Location: fs/ext4/mballoc.c:2796
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_process_freed_data
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
