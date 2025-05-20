# Function: <code>__do_sys_setpriority</code>

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
In kernel/sys.c (ffffffff810a33fa)
Location: kernel/sys.c:196
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
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
In kernel/sys.c (ffffffff810af29a)
Location: kernel/sys.c:196
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
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
In kernel/sys.c (ffffffff810b14ba)
Location: kernel/sys.c:196
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
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
In kernel/sys.c (ffffffff810b7b8a)
Location: kernel/sys.c:196
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_setpriority(int which, int who, int niceval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810c07f0)
Location: kernel/sys.c:197
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
**Symbols:**

```
ffffffff810c07f0-ffffffff810c0a82: __do_sys_setpriority (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_setpriority(int which, int who, int niceval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bb960)
Location: kernel/sys.c:198
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
**Symbols:**

```
ffffffff810bb960-ffffffff810bbbf1: __do_sys_setpriority (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_setpriority(int which, int who, int niceval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810bd210)
Location: kernel/sys.c:203
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
**Symbols:**

```
ffffffff810bd210-ffffffff810bd49c: __do_sys_setpriority (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_setpriority(int which, int who, int niceval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810cfec0)
Location: kernel/sys.c:203
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
**Symbols:**

```
ffffffff810cfec0-ffffffff810d014c: __do_sys_setpriority (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_setpriority(int which, int who, int niceval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff810e6e50)
Location: kernel/sys.c:210
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
**Symbols:**

```
ffffffff810e6e50-ffffffff810e713e: __do_sys_setpriority (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_setpriority(int which, int who, int niceval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81107a30)
Location: kernel/sys.c:211
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
**Symbols:**

```
ffffffff81107a30-ffffffff81107d1e: __do_sys_setpriority (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_setpriority(int which, int who, int niceval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff81113d30)
Location: kernel/sys.c:218
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
**Symbols:**

```
ffffffff81113d30-ffffffff81114028: __do_sys_setpriority (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_setpriority(int which, int who, int niceval);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sys.c (ffffffff8111d720)
Location: kernel/sys.c:218
Inline: False
Direct callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
```
**Symbols:**

```
ffffffff8111d720-ffffffff8111da18: __do_sys_setpriority (STB_LOCAL)
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
In kernel/sys.c (ffff800010114cd8)
Location: kernel/sys.c:196
Inline: True
Inline callers:
  - kernel/sys.c:__arm64_sys_setpriority
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
In kernel/sys.c (c036b9b8)
Location: kernel/sys.c:196
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setpriority
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
In kernel/sys.c (c00000000015bf48)
Location: kernel/sys.c:196
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setpriority
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
In kernel/sys.c (ffffffe0000d2b30)
Location: kernel/sys.c:196
Inline: True
Inline callers:
  - kernel/sys.c:__se_sys_setpriority
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
In kernel/sys.c (ffffffff810b1efa)
Location: kernel/sys.c:196
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
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
In kernel/sys.c (ffffffff810a081a)
Location: kernel/sys.c:196
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
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
In kernel/sys.c (ffffffff810b145a)
Location: kernel/sys.c:196
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
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
In kernel/sys.c (ffffffff810bce0a)
Location: kernel/sys.c:196
Inline: True
Inline callers:
  - kernel/sys.c:__ia32_sys_setpriority
  - kernel/sys.c:__x64_sys_setpriority
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
