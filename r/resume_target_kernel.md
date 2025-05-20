# Function: <code>resume_target_kernel</code>

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
In kernel/power/hibernate.c (ffffffff810cf82e)
Location: kernel/power/hibernate.c:421
Inline: True
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
In kernel/power/hibernate.c (ffffffff810d42de)
Location: kernel/power/hibernate.c:428
Inline: True
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
In kernel/power/hibernate.c (ffffffff810dae8e)
Location: kernel/power/hibernate.c:430
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
In kernel/power/hibernate.c (ffffffff810d9f9e)
Location: kernel/power/hibernate.c:429
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
In kernel/power/hibernate.c (ffffffff810e2202)
Location: kernel/power/hibernate.c:429
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
In kernel/power/hibernate.c (ffffffff810ea5ee)
Location: kernel/power/hibernate.c:432
Inline: True
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
In kernel/power/hibernate.c (ffffffff810f5c1e)
Location: kernel/power/hibernate.c:432
Inline: True
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
In kernel/power/hibernate.c (ffffffff810fe19e)
Location: kernel/power/hibernate.c:439
Inline: True
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
In kernel/power/hibernate.c (ffffffff8110a5ce)
Location: kernel/power/hibernate.c:440
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int resume_target_kernel(bool platform_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:452
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_restore
```
**Symbols:**

```
ffffffff811151f0-ffffffff811152e6: resume_target_kernel (STB_LOCAL)
ffffffff8111593c-ffffffff81115950: resume_target_kernel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int resume_target_kernel(bool platform_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:452
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_restore
```
**Symbols:**

```
ffffffff81111b80-ffffffff81111c76: resume_target_kernel (STB_LOCAL)
ffffffff81bdf1cf-ffffffff81bdf1e3: resume_target_kernel.cold (STB_LOCAL)
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
In kernel/power/hibernate.c (ffffffff811125fe)
Location: kernel/power/hibernate.c:452
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_restore
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
In kernel/power/hibernate.c (ffffffff8113262e)
Location: kernel/power/hibernate.c:455
Inline: True
Inline callers:
  - kernel/power/hibernate.c:hibernation_restore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int resume_target_kernel(bool platform_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/hibernate.c (0)
Location: kernel/power/hibernate.c:454
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_restore
```
**Symbols:**

```
ffffffff81154400-ffffffff81154513: resume_target_kernel (STB_LOCAL)
ffffffff81e59f11-ffffffff81e59f24: resume_target_kernel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int resume_target_kernel(bool platform_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81183bf0)
Location: kernel/power/hibernate.c:458
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_restore
```
**Symbols:**

```
ffffffff81183bf0-ffffffff81183d2c: resume_target_kernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int resume_target_kernel(bool platform_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff81194a60)
Location: kernel/power/hibernate.c:459
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_restore
```
**Symbols:**

```
ffffffff81194a60-ffffffff81194b9c: resume_target_kernel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int resume_target_kernel(bool platform_mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff811a3450)
Location: kernel/power/hibernate.c:459
Inline: False
Direct callers:
  - kernel/power/hibernate.c:hibernation_restore
```
**Symbols:**

```
ffffffff811a3450-ffffffff811a358c: resume_target_kernel (STB_LOCAL)
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (c03bccd8)
Location: kernel/power/hibernate.c:440
Inline: True
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/hibernate.c (ffffffff8110282e)
Location: kernel/power/hibernate.c:440
Inline: True
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
In kernel/power/hibernate.c (ffffffff810f3aae)
Location: kernel/power/hibernate.c:440
Inline: True
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
In kernel/power/hibernate.c (ffffffff81100a9e)
Location: kernel/power/hibernate.c:440
Inline: True
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
In kernel/power/hibernate.c (ffffffff8110be6e)
Location: kernel/power/hibernate.c:440
Inline: True
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
