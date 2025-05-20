# Function: <code>clone_uts_ns</code>

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
In kernel/utsname.c (ffffffff8111dd00)
Location: kernel/utsname.c:35
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffff81125bd7)
Location: kernel/utsname.c:35
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffff8112f5eb)
Location: kernel/utsname.c:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffff81130b5f)
Location: kernel/utsname.c:47
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffff8113dab0)
Location: kernel/utsname.c:47
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffff8114c463)
Location: kernel/utsname.c:49
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffff81159083)
Location: kernel/utsname.c:49
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffff811657b8)
Location: kernel/utsname.c:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffff81171678)
Location: kernel/utsname.c:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct uts_namespace *clone_uts_ns(struct user_namespace *user_ns, struct uts_namespace *old_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/utsname.c (ffffffff81183280)
Location: kernel/utsname.c:45
Inline: False
Direct callers:
  - kernel/utsname.c:copy_utsname
```
**Symbols:**

```
ffffffff81183280-ffffffff811833cc: clone_uts_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct uts_namespace *clone_uts_ns(struct user_namespace *user_ns, struct uts_namespace *old_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/utsname.c (ffffffff81180170)
Location: kernel/utsname.c:45
Inline: False
Direct callers:
  - kernel/utsname.c:copy_utsname
```
**Symbols:**

```
ffffffff81180170-ffffffff811802ce: clone_uts_ns (STB_LOCAL)
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
In kernel/utsname.c (ffffffff8118136a)
Location: kernel/utsname.c:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffff811a92da)
Location: kernel/utsname.c:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct uts_namespace *clone_uts_ns(struct user_namespace *user_ns, struct uts_namespace *old_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/utsname.c (ffffffff811da410)
Location: kernel/utsname.c:45
Inline: False
Direct callers:
  - kernel/utsname.c:copy_utsname
```
**Symbols:**

```
ffffffff811da410-ffffffff811da586: clone_uts_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct uts_namespace *clone_uts_ns(struct user_namespace *user_ns, struct uts_namespace *old_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/utsname.c (ffffffff8121f9d0)
Location: kernel/utsname.c:45
Inline: False
Direct callers:
  - kernel/utsname.c:copy_utsname
```
**Symbols:**

```
ffffffff8121f9d0-ffffffff8121fb46: clone_uts_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct uts_namespace *clone_uts_ns(struct user_namespace *user_ns, struct uts_namespace *old_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/utsname.c (ffffffff81235bc0)
Location: kernel/utsname.c:45
Inline: False
Direct callers:
  - kernel/utsname.c:copy_utsname
```
**Symbols:**

```
ffffffff81235bc0-ffffffff81235d36: clone_uts_ns (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct uts_namespace *clone_uts_ns(struct user_namespace *user_ns, struct uts_namespace *old_ns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/utsname.c (ffffffff8124f840)
Location: kernel/utsname.c:45
Inline: False
Direct callers:
  - kernel/utsname.c:copy_utsname
```
**Symbols:**

```
ffffffff8124f840-ffffffff8124f9b6: clone_uts_ns (STB_LOCAL)
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
In kernel/utsname.c (ffff8000101e5294)
Location: kernel/utsname.c:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (c0425b30)
Location: kernel/utsname.c:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (c000000000255670)
Location: kernel/utsname.c:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffe00015af7e)
Location: kernel/utsname.c:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffff81169c98)
Location: kernel/utsname.c:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffff8115ce98)
Location: kernel/utsname.c:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffff81167a68)
Location: kernel/utsname.c:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
In kernel/utsname.c (ffffffff81175148)
Location: kernel/utsname.c:45
Inline: True
Inline callers:
  - kernel/utsname.c:copy_utsname
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
