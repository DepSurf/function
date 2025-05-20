# Function: <code>__get_seccomp_filter</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8115bf90)
Location: kernel/seccomp.c:477
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_get_filter
```
**Symbols:**

```
ffffffff8115bf90-ffffffff8115bfa4: __get_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8116aba0)
Location: kernel/seccomp.c:486
Inline: False
```
**Symbols:**

```
ffffffff8116aba0-ffffffff8116abb4: __get_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81177ce0)
Location: kernel/seccomp.c:547
Inline: False
```
**Symbols:**

```
ffffffff81177ce0-ffffffff81177cf4: __get_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81184a80)
Location: kernel/seccomp.c:552
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
**Symbols:**

```
ffffffff81184a80-ffffffff81184a94: __get_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81190900)
Location: kernel/seccomp.c:553
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff81190900-ffffffff81190914: __get_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a6660)
Location: kernel/seccomp.c:563
Inline: True
Inline callers:
  - kernel/seccomp.c:init_listener
  - kernel/seccomp.c:seccomp_attach_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a3b33)
Location: kernel/seccomp.c:905
Inline: True
Inline callers:
  - kernel/seccomp.c:init_listener
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/seccomp.c (ffffffff811a552d)
Location: kernel/seccomp.c:910
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/seccomp.c (ffffffff811cec7d)
Location: kernel/seccomp.c:913
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/seccomp.c (ffffffff81202dd6)
Location: kernel/seccomp.c:919
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/seccomp.c (ffffffff8124ac36)
Location: kernel/seccomp.c:919
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/seccomp.c (ffffffff81261f36)
Location: kernel/seccomp.c:919
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/seccomp.c (ffffffff8127c181)
Location: kernel/seccomp.c:928
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/seccomp.c (ffff800010209bd0)
Location: kernel/seccomp.c:553
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (c0448c8c)
Location: kernel/seccomp.c:553
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
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
In kernel/seccomp.c (c000000000286f14)
Location: kernel/seccomp.c:553
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffe00016bcf2)
Location: kernel/seccomp.c:553
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_attach_filter
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81188f20)
Location: kernel/seccomp.c:553
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff81188f20-ffffffff81188f34: __get_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8117c060)
Location: kernel/seccomp.c:553
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff8117c060-ffffffff8117c074: __get_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81186cf0)
Location: kernel/seccomp.c:553
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff81186cf0-ffffffff81186d04: __get_seccomp_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __get_seccomp_filter(struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81194640)
Location: kernel/seccomp.c:553
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff81194640-ffffffff81194654: __get_seccomp_filter (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
