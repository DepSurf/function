# Function: <code>seccomp_set_mode_strict</code>

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
In kernel/seccomp.c (ffffffff8113b83b)
Location: kernel/seccomp.c:728
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
In kernel/seccomp.c (ffffffff81143ff3)
Location: kernel/seccomp.c:693
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
In kernel/seccomp.c (ffffffff8114dea6)
Location: kernel/seccomp.c:692
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
In kernel/seccomp.c (ffffffff811503e8)
Location: kernel/seccomp.c:785
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
In kernel/seccomp.c (ffffffff8115c60c)
Location: kernel/seccomp.c:808
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
In kernel/seccomp.c (ffffffff8116b9be)
Location: kernel/seccomp.c:814
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
In kernel/seccomp.c (ffffffff81179206)
Location: kernel/seccomp.c:951
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
In kernel/seccomp.c (ffffffff8118665d)
Location: kernel/seccomp.c:956
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
In kernel/seccomp.c (ffffffff811925dd)
Location: kernel/seccomp.c:967
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int seccomp_set_mode_strict();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a6c20)
Location: kernel/seccomp.c:977
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
```
**Symbols:**

```
ffffffff811a6c20-ffffffff811a6cc8: seccomp_set_mode_strict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int seccomp_set_mode_strict();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a4220)
Location: kernel/seccomp.c:1328
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
```
**Symbols:**

```
ffffffff811a4220-ffffffff811a42c8: seccomp_set_mode_strict (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff811a5796)
Location: kernel/seccomp.c:1358
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
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
In kernel/seccomp.c (ffffffff811ceee6)
Location: kernel/seccomp.c:1340
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
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
In kernel/seccomp.c (ffffffff8120302c)
Location: kernel/seccomp.c:1366
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
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
In kernel/seccomp.c (ffffffff8124ae9c)
Location: kernel/seccomp.c:1366
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
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
In kernel/seccomp.c (ffffffff8126220d)
Location: kernel/seccomp.c:1366
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
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
In kernel/seccomp.c (ffffffff8127c44d)
Location: kernel/seccomp.c:1378
Inline: True
Inline callers:
  - kernel/seccomp.c:do_seccomp
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
In kernel/seccomp.c (ffff800010209f50)
Location: kernel/seccomp.c:967
Inline: True
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
In kernel/seccomp.c (c0448e48)
Location: kernel/seccomp.c:967
Inline: True
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
In kernel/seccomp.c (c000000000287330)
Location: kernel/seccomp.c:967
Inline: True
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
In kernel/seccomp.c (ffffffe00016bdd6)
Location: kernel/seccomp.c:967
Inline: True
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
In kernel/seccomp.c (ffffffff8118abfd)
Location: kernel/seccomp.c:967
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
In kernel/seccomp.c (ffffffff8117dd1d)
Location: kernel/seccomp.c:967
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
In kernel/seccomp.c (ffffffff811889cd)
Location: kernel/seccomp.c:967
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
In kernel/seccomp.c (ffffffff81196337)
Location: kernel/seccomp.c:967
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
</ul>
