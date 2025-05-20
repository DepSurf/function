# Function: <code>kimage_load_normal_segment</code>

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
In kernel/kexec_core.c (ffffffff8110d260)
Location: kernel/kexec_core.c:704
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (ffffffff81114b3d)
Location: kernel/kexec_core.c:724
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (ffffffff8111c230)
Location: kernel/kexec_core.c:726
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (ffffffff8111e102)
Location: kernel/kexec_core.c:760
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (ffffffff811298f2)
Location: kernel/kexec_core.c:770
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (ffffffff811376b0)
Location: kernel/kexec_core.c:770
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (ffffffff81142e50)
Location: kernel/kexec_core.c:775
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (ffffffff8114e1a0)
Location: kernel/kexec_core.c:773
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (ffffffff81159eb0)
Location: kernel/kexec_core.c:775
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kimage_load_normal_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8116a6b0)
Location: kernel/kexec_core.c:781
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff8116a6b0-ffffffff8116a904: kimage_load_normal_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kimage_load_normal_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81166df0)
Location: kernel/kexec_core.c:780
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff81166df0-ffffffff81167044: kimage_load_normal_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kimage_load_normal_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81167b90)
Location: kernel/kexec_core.c:781
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff81167b90-ffffffff81167dde: kimage_load_normal_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kimage_load_normal_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8118d4b0)
Location: kernel/kexec_core.c:782
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff8118d4b0-ffffffff8118d6fe: kimage_load_normal_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kimage_load_normal_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811bc980)
Location: kernel/kexec_core.c:781
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff811bc980-ffffffff811bcbdd: kimage_load_normal_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kimage_load_normal_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811fe920)
Location: kernel/kexec_core.c:770
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff811fe920-ffffffff811feb6e: kimage_load_normal_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kimage_load_normal_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81213d20)
Location: kernel/kexec_core.c:771
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff81213d20-ffffffff81213f6e: kimage_load_normal_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kimage_load_normal_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8122bc70)
Location: kernel/kexec_core.c:759
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff8122bc70-ffffffff8122bebe: kimage_load_normal_segment (STB_LOCAL)
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
In kernel/kexec_core.c (ffff8000101c95bc)
Location: kernel/kexec_core.c:775
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (c0410450)
Location: kernel/kexec_core.c:775
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (c000000000231e5c)
Location: kernel/kexec_core.c:775
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (ffffffff811524d0)
Location: kernel/kexec_core.c:775
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (ffffffff811457b0)
Location: kernel/kexec_core.c:775
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (ffffffff81150380)
Location: kernel/kexec_core.c:775
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
In kernel/kexec_core.c (ffffffff8115d1d3)
Location: kernel/kexec_core.c:775
Inline: True
Inline callers:
  - kernel/kexec_core.c:kimage_load_segment
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
