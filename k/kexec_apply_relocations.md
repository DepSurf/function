# Function: <code>kexec_apply_relocations</code>

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
In kernel/kexec_file.c (ffffffff8110ee0d)
Location: kernel/kexec_file.c:843
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff8111649d)
Location: kernel/kexec_file.c:796
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff8111dbea)
Location: kernel/kexec_file.c:821
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff8111f7c9)
Location: kernel/kexec_file.c:822
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff8112af69)
Location: kernel/kexec_file.c:824
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff811393d3)
Location: kernel/kexec_file.c:843
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff81144ca3)
Location: kernel/kexec_file.c:901
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff811500a2)
Location: kernel/kexec_file.c:946
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff8115bd32)
Location: kernel/kexec_file.c:951
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kexec_apply_relocations(struct kimage *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116c680)
Location: kernel/kexec_file.c:938
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8116c680-ffffffff8116c756: kexec_apply_relocations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kexec_apply_relocations(struct kimage *image);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81168cc0)
Location: kernel/kexec_file.c:956
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81168cc0-ffffffff81168d96: kexec_apply_relocations (STB_LOCAL)
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
In kernel/kexec_file.c (ffffffff8116a0d9)
Location: kernel/kexec_file.c:958
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff8118fc99)
Location: kernel/kexec_file.c:958
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff811bf44e)
Location: kernel/kexec_file.c:917
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff812016fe)
Location: kernel/kexec_file.c:921
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff81216ace)
Location: kernel/kexec_file.c:937
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff8122e9ae)
Location: kernel/kexec_file.c:953
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (c0000000002343cc)
Location: kernel/kexec_file.c:951
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff81154352)
Location: kernel/kexec_file.c:951
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff81147672)
Location: kernel/kexec_file.c:951
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff81152132)
Location: kernel/kexec_file.c:951
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
In kernel/kexec_file.c (ffffffff8115f022)
Location: kernel/kexec_file.c:951
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
