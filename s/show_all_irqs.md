# Function: <code>show_all_irqs</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff81363da7)
Location: fs/proc/stat.c:95
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (ffffffff8137c087)
Location: fs/proc/stat.c:95
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void show_all_irqs(struct seq_file *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff813c5280)
Location: fs/proc/stat.c:95
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff813c5280-ffffffff813c5348: show_all_irqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_all_irqs(struct seq_file *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/stat.c (ffffffff813d71d0)
Location: fs/proc/stat.c:96
Inline: False
Direct callers:
  - fs/proc/stat.c:show_stat
```
**Symbols:**

```
ffffffff813d71d0-ffffffff813d7298: show_all_irqs (STB_LOCAL)
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
In fs/proc/stat.c (ffffffff813de791)
Location: fs/proc/stat.c:96
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (ffffffff8142ffd6)
Location: fs/proc/stat.c:96
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (ffffffff814a9c4d)
Location: fs/proc/stat.c:96
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (ffffffff8153f76b)
Location: fs/proc/stat.c:96
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (ffffffff81577ac0)
Location: fs/proc/stat.c:70
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (ffffffff815b0302)
Location: fs/proc/stat.c:70
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (ffff8000104487f0)
Location: fs/proc/stat.c:95
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (c060d8bc)
Location: fs/proc/stat.c:95
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (c00000000055ee2c)
Location: fs/proc/stat.c:95
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (ffffffe0002de368)
Location: fs/proc/stat.c:95
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (ffffffff81374667)
Location: fs/proc/stat.c:95
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (ffffffff81365137)
Location: fs/proc/stat.c:95
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (ffffffff81372137)
Location: fs/proc/stat.c:95
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
In fs/proc/stat.c (ffffffff81385b17)
Location: fs/proc/stat.c:95
Inline: True
Inline callers:
  - fs/proc/stat.c:show_stat
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
