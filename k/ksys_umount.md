# Function: <code>ksys_umount</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812bfad0)
Location: fs/namespace.c:1717
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
```
**Symbols:**

```
ffffffff812bfad0-ffffffff812bfef0: ksys_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d4cd0)
Location: fs/namespace.c:1635
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
```
**Symbols:**

```
ffffffff812d4cd0-ffffffff812d510f: ksys_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f2180)
Location: fs/namespace.c:1670
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
```
**Symbols:**

```
ffffffff812f2180-ffffffff812f2604: ksys_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81303d40)
Location: fs/namespace.c:1675
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
```
**Symbols:**

```
ffffffff81303d40-ffffffff813041c1: ksys_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133dc10)
Location: fs/namespace.c:1725
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
```
**Symbols:**

```
ffffffff8133dc10-ffffffff8133dd3c: ksys_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81349d6c)
Location: fs/namespace.c:1753
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__x64_sys_umount
Direct callers:
  - fs/namespace.c:__ia32_sys_umount
```
**Symbols:**

```
ffffffff81349c40-ffffffff81349cba: ksys_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8135075c)
Location: fs/namespace.c:1768
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__x64_sys_umount
Direct callers:
  - fs/namespace.c:__ia32_sys_umount
```
**Symbols:**

```
ffffffff81350630-ffffffff813506aa: ksys_umount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139eb1c)
Location: fs/namespace.c:1769
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__x64_sys_umount
Direct callers:
  - fs/namespace.c:__ia32_sys_umount
```
**Symbols:**

```
ffffffff8139e9f0-ffffffff8139ea6a: ksys_umount (STB_LOCAL)
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
In fs/namespace.c (ffffffff81421d7c)
Location: fs/namespace.c:1810
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
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
In fs/namespace.c (ffffffff814ae36c)
Location: fs/namespace.c:1915
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
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
In fs/namespace.c (ffffffff814e330c)
Location: fs/namespace.c:1902
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
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
In fs/namespace.c (ffffffff8151705c)
Location: fs/namespace.c:1904
Inline: True
Inline callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103b7460)
Location: fs/namespace.c:1675
Inline: False
Direct callers:
  - fs/namespace.c:__arm64_sys_umount
```
**Symbols:**

```
ffff8000103b7460-ffff8000103b79f4: ksys_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0595abc)
Location: fs/namespace.c:1675
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_umount
```
**Symbols:**

```
c0595abc-c0595c10: ksys_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b3ff0)
Location: fs/namespace.c:1675
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_oldumount
  - fs/namespace.c:__se_sys_umount
```
**Symbols:**

```
c0000000004b3ff0-c0000000004b4638: ksys_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffe00027a026)
Location: fs/namespace.c:1675
Inline: False
Direct callers:
  - fs/namespace.c:__se_sys_umount
```
**Symbols:**

```
ffffffe00027a026-ffffffe00027a46c: ksys_umount (STB_GLOBAL)
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
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fc320)
Location: fs/namespace.c:1675
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
```
**Symbols:**

```
ffffffff812fc320-ffffffff812fc7a1: ksys_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ecf40)
Location: fs/namespace.c:1675
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
```
**Symbols:**

```
ffffffff812ecf40-ffffffff812ed3c1: ksys_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fa110)
Location: fs/namespace.c:1675
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
```
**Symbols:**

```
ffffffff812fa110-ffffffff812fa591: ksys_umount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ksys_umount(char *name, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130b450)
Location: fs/namespace.c:1675
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_oldumount
  - fs/namespace.c:__x64_sys_oldumount
  - fs/namespace.c:__ia32_sys_umount
  - fs/namespace.c:__x64_sys_umount
```
**Symbols:**

```
ffffffff8130b450-ffffffff8130b8cd: ksys_umount (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
