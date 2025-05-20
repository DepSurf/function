# Function: <code>__do_sys_olduname</code>

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
In kernel/sys.c (ffffffff810a5c1f)
Location: kernel/sys.c:1294
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810ae91f)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810b331f)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810b990f)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_olduname(struct oldold_utsname *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c0bf0)
Location: kernel/sys.c:1309
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
```
**Symbols:**

```
ffffffff810c0bf0-ffffffff810c0d31: __do_sys_olduname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_olduname(struct oldold_utsname *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bbd60)
Location: kernel/sys.c:1310
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
```
**Symbols:**

```
ffffffff810bbd60-ffffffff810bbea0: __do_sys_olduname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_olduname(struct oldold_utsname *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bd600)
Location: kernel/sys.c:1327
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
```
**Symbols:**

```
ffffffff810bd600-ffffffff810bd740: __do_sys_olduname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_olduname(struct oldold_utsname *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810cfca0)
Location: kernel/sys.c:1336
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
```
**Symbols:**

```
ffffffff810cfca0-ffffffff810cfde0: __do_sys_olduname (STB_LOCAL)
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
In kernel/sys.c (ffffffff810e8564)
Location: kernel/sys.c:1343
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff81109354)
Location: kernel/sys.c:1344
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff81115664)
Location: kernel/sys.c:1362
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff8111f054)
Location: kernel/sys.c:1362
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (c00000000015da0c)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_olduname
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
In kernel/sys.c (ffffffff810b3c7f)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810a25af)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810b31df)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
In kernel/sys.c (ffffffff810bbbff)
Location: kernel/sys.c:1295
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_olduname
  - kernel/sys.c:__x64_sys_olduname
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
</ul>
