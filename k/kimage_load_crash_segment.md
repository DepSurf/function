# Function: <code>kimage_load_crash_segment</code>

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
In kernel/kexec_core.c (ffffffff8110d0f8)
Location: kernel/kexec_core.c:771
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
In kernel/kexec_core.c (ffffffff81114a18)
Location: kernel/kexec_core.c:791
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
In kernel/kexec_core.c (ffffffff8111c128)
Location: kernel/kexec_core.c:793
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
In kernel/kexec_core.c (ffffffff8111df73)
Location: kernel/kexec_core.c:827
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
In kernel/kexec_core.c (ffffffff81129763)
Location: kernel/kexec_core.c:837
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
In kernel/kexec_core.c (ffffffff811378a8)
Location: kernel/kexec_core.c:839
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
In kernel/kexec_core.c (ffffffff81143048)
Location: kernel/kexec_core.c:844
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
In kernel/kexec_core.c (ffffffff8114e399)
Location: kernel/kexec_core.c:842
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
In kernel/kexec_core.c (ffffffff8115a0a9)
Location: kernel/kexec_core.c:844
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
int kimage_load_crash_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8116a040)
Location: kernel/kexec_core.c:850
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff8116a040-ffffffff8116a33c: kimage_load_crash_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kimage_load_crash_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81166780)
Location: kernel/kexec_core.c:849
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff81166780-ffffffff81166a7c: kimage_load_crash_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kimage_load_crash_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81167520)
Location: kernel/kexec_core.c:850
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff81167520-ffffffff81167819: kimage_load_crash_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kimage_load_crash_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8118ccd0)
Location: kernel/kexec_core.c:851
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff8118ccd0-ffffffff8118cfc9: kimage_load_crash_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kimage_load_crash_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811bc300)
Location: kernel/kexec_core.c:849
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff811bc300-ffffffff811bc5bb: kimage_load_crash_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kimage_load_crash_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff811fe180)
Location: kernel/kexec_core.c:838
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff811fe180-ffffffff811fe436: kimage_load_crash_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kimage_load_crash_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff81213440)
Location: kernel/kexec_core.c:839
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff81213440-ffffffff812136f6: kimage_load_crash_segment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kimage_load_crash_segment(struct kimage *image, struct kexec_segment *segment);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_core.c (ffffffff8122b370)
Location: kernel/kexec_core.c:827
Inline: False
Direct callers:
  - kernel/kexec_core.c:kimage_load_segment
```
**Symbols:**

```
ffffffff8122b370-ffffffff8122b626: kimage_load_crash_segment (STB_LOCAL)
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
In kernel/kexec_core.c (ffff8000101c9734)
Location: kernel/kexec_core.c:844
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
In kernel/kexec_core.c (c0410668)
Location: kernel/kexec_core.c:844
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
In kernel/kexec_core.c (c0000000002320ec)
Location: kernel/kexec_core.c:844
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
In kernel/kexec_core.c (ffffffff811526c9)
Location: kernel/kexec_core.c:844
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
In kernel/kexec_core.c (ffffffff811459a9)
Location: kernel/kexec_core.c:844
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
In kernel/kexec_core.c (ffffffff81150579)
Location: kernel/kexec_core.c:844
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
In kernel/kexec_core.c (ffffffff8115d3a7)
Location: kernel/kexec_core.c:844
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
