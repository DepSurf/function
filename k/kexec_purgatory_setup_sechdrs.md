# Function: <code>kexec_purgatory_setup_sechdrs</code>

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
In kernel/kexec_file.c (ffffffff811392ae)
Location: kernel/kexec_file.c:784
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
In kernel/kexec_file.c (ffffffff81144b7e)
Location: kernel/kexec_file.c:842
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
In kernel/kexec_file.c (ffffffff8114ff81)
Location: kernel/kexec_file.c:887
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
In kernel/kexec_file.c (ffffffff8115bc11)
Location: kernel/kexec_file.c:892
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
int kexec_purgatory_setup_sechdrs(struct purgatory_info *pi, struct kexec_buf *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116c110)
Location: kernel/kexec_file.c:879
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8116c110-ffffffff8116c26d: kexec_purgatory_setup_sechdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kexec_purgatory_setup_sechdrs(struct purgatory_info *pi, struct kexec_buf *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811687b0)
Location: kernel/kexec_file.c:897
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff811687b0-ffffffff8116890d: kexec_purgatory_setup_sechdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kexec_purgatory_setup_sechdrs(struct purgatory_info *pi, struct kexec_buf *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81169550)
Location: kernel/kexec_file.c:899
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81169550-ffffffff811696b1: kexec_purgatory_setup_sechdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kexec_purgatory_setup_sechdrs(struct purgatory_info *pi, struct kexec_buf *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8118efb0)
Location: kernel/kexec_file.c:899
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8118efb0-ffffffff8118f111: kexec_purgatory_setup_sechdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kexec_purgatory_setup_sechdrs(struct purgatory_info *pi, struct kexec_buf *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811be710)
Location: kernel/kexec_file.c:858
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff811be710-ffffffff811be882: kexec_purgatory_setup_sechdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kexec_purgatory_setup_sechdrs(struct purgatory_info *pi, struct kexec_buf *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81200990)
Location: kernel/kexec_file.c:862
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81200990-ffffffff81200b03: kexec_purgatory_setup_sechdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kexec_purgatory_setup_sechdrs(struct purgatory_info *pi, struct kexec_buf *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81215d90)
Location: kernel/kexec_file.c:865
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81215d90-ffffffff81215f12: kexec_purgatory_setup_sechdrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kexec_purgatory_setup_sechdrs(struct purgatory_info *pi, struct kexec_buf *kbuf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8122dd60)
Location: kernel/kexec_file.c:881
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8122dd60-ffffffff8122dee2: kexec_purgatory_setup_sechdrs (STB_LOCAL)
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
In kernel/kexec_file.c (c000000000234294)
Location: kernel/kexec_file.c:892
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
In kernel/kexec_file.c (ffffffff81154231)
Location: kernel/kexec_file.c:892
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
In kernel/kexec_file.c (ffffffff81147551)
Location: kernel/kexec_file.c:892
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
In kernel/kexec_file.c (ffffffff81152011)
Location: kernel/kexec_file.c:892
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
In kernel/kexec_file.c (ffffffff8115ef01)
Location: kernel/kexec_file.c:892
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
