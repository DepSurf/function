# Function: <code>build_map_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81187ae9)
Location: kernel/events/uprobes.c:711
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8119a199)
Location: kernel/events/uprobes.c:713
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
In kernel/events/uprobes.c (ffffffff811a9909)
Location: kernel/events/uprobes.c:714
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
In kernel/events/uprobes.c (ffffffff811b0f7d)
Location: kernel/events/uprobes.c:722
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
In kernel/events/uprobes.c (ffffffff811c4b5d)
Location: kernel/events/uprobes.c:722
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
In kernel/events/uprobes.c (ffffffff811e50a2)
Location: kernel/events/uprobes.c:720
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
In kernel/events/uprobes.c (ffffffff811f5a2e)
Location: kernel/events/uprobes.c:936
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
In kernel/events/uprobes.c (ffffffff8120d7b5)
Location: kernel/events/uprobes.c:924
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
In kernel/events/uprobes.c (ffffffff8121ade5)
Location: kernel/events/uprobes.c:976
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct map_info *build_map_info(struct address_space *mapping, loff_t offset, bool is_register);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81245750)
Location: kernel/events/uprobes.c:966
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff81245750-ffffffff8124591c: build_map_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct map_info *build_map_info(struct address_space *mapping, loff_t offset, bool is_register);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8124fd70)
Location: kernel/events/uprobes.c:966
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff8124fd70-ffffffff8124ff3c: build_map_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct map_info *build_map_info(struct address_space *mapping, loff_t offset, bool is_register);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81254650)
Location: kernel/events/uprobes.c:964
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff81254650-ffffffff8125481c: build_map_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct map_info *build_map_info(struct address_space *mapping, loff_t offset, bool is_register);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81290080)
Location: kernel/events/uprobes.c:965
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff81290080-ffffffff8129024c: build_map_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct map_info *build_map_info(struct address_space *mapping, loff_t offset, bool is_register);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e5140)
Location: kernel/events/uprobes.c:959
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff812e5140-ffffffff812e5316: build_map_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct map_info *build_map_info(struct address_space *mapping, loff_t offset, bool is_register);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8134eaf0)
Location: kernel/events/uprobes.c:962
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff8134eaf0-ffffffff8134ecc0: build_map_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct map_info *build_map_info(struct address_space *mapping, loff_t offset, bool is_register);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8137fc80)
Location: kernel/events/uprobes.c:959
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff8137fc80-ffffffff8137fe5c: build_map_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct map_info *build_map_info(struct address_space *mapping, loff_t offset, bool is_register);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813a8e90)
Location: kernel/events/uprobes.c:959
Inline: False
Direct callers:
  - kernel/events/uprobes.c:register_for_each_vma
```
**Symbols:**

```
ffffffff813a8e90-ffffffff813a90e0: build_map_info (STB_LOCAL)
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
In kernel/events/uprobes.c (ffff8000102a6488)
Location: kernel/events/uprobes.c:976
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
In kernel/events/uprobes.c (c04d55b4)
Location: kernel/events/uprobes.c:976
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
In kernel/events/uprobes.c (c0000000003593ec)
Location: kernel/events/uprobes.c:976
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
In kernel/events/uprobes.c (ffffffff81213435)
Location: kernel/events/uprobes.c:976
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
In kernel/events/uprobes.c (ffffffff812061a5)
Location: kernel/events/uprobes.c:976
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
In kernel/events/uprobes.c (ffffffff812111d5)
Location: kernel/events/uprobes.c:976
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
In kernel/events/uprobes.c (ffffffff81220125)
Location: kernel/events/uprobes.c:976
Inline: True
Inline callers:
  - kernel/events/uprobes.c:register_for_each_vma
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
