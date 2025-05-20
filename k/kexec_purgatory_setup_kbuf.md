# Function: <code>kexec_purgatory_setup_kbuf</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811391af)
Location: kernel/kexec_file.c:723
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
In kernel/kexec_file.c (ffffffff81144a7f)
Location: kernel/kexec_file.c:781
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
In kernel/kexec_file.c (ffffffff8114fe8c)
Location: kernel/kexec_file.c:826
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
In kernel/kexec_file.c (ffffffff8115bb1c)
Location: kernel/kexec_file.c:831
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
int kexec_purgatory_setup_kbuf(struct purgatory_info *pi, struct kexec_buf *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116cc20)
Location: kernel/kexec_file.c:818
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8116cc20-ffffffff8116cd67: kexec_purgatory_setup_kbuf (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kexec_purgatory_setup_kbuf(struct purgatory_info *pi, struct kexec_buf *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811692a0)
Location: kernel/kexec_file.c:836
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff811692a0-ffffffff811693e7: kexec_purgatory_setup_kbuf (STB_LOCAL)
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
In kernel/kexec_file.c (ffffffff81169f9c)
Location: kernel/kexec_file.c:838
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
In kernel/kexec_file.c (ffffffff8118fb5c)
Location: kernel/kexec_file.c:838
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
In kernel/kexec_file.c (ffffffff811bf2fc)
Location: kernel/kexec_file.c:797
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
In kernel/kexec_file.c (ffffffff812015ac)
Location: kernel/kexec_file.c:801
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
In kernel/kexec_file.c (ffffffff8121697c)
Location: kernel/kexec_file.c:804
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
In kernel/kexec_file.c (ffffffff8122e85c)
Location: kernel/kexec_file.c:820
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
In kernel/kexec_file.c (c00000000023415c)
Location: kernel/kexec_file.c:831
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
In kernel/kexec_file.c (ffffffff8115413c)
Location: kernel/kexec_file.c:831
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
In kernel/kexec_file.c (ffffffff8114745c)
Location: kernel/kexec_file.c:831
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
In kernel/kexec_file.c (ffffffff81151f1c)
Location: kernel/kexec_file.c:831
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
In kernel/kexec_file.c (ffffffff8115ee0c)
Location: kernel/kexec_file.c:831
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
