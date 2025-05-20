# Function: <code>__do_sys_mlockall</code>

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
In mm/mlock.c (ffffffff81233d52)
Location: mm/mlock.c:795
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
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
In mm/mlock.c (ffffffff81247322)
Location: mm/mlock.c:795
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
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
In mm/mlock.c (ffffffff81259532)
Location: mm/mlock.c:795
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
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
In mm/mlock.c (ffffffff81267a02)
Location: mm/mlock.c:799
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_mlockall(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81297b20)
Location: mm/mlock.c:799
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff81297b20-ffffffff81297cd5: __do_sys_mlockall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_mlockall(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a2be0)
Location: mm/mlock.c:775
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff812a2be0-ffffffff812a2dda: __do_sys_mlockall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_mlockall(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a8460)
Location: mm/mlock.c:774
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff812a8460-ffffffff812a8637: __do_sys_mlockall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_mlockall(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812e9aa0)
Location: mm/mlock.c:775
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff812e9aa0-ffffffff812e9c7e: __do_sys_mlockall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_mlockall(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81349e90)
Location: mm/mlock.c:696
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff81349e90-ffffffff8134a095: __do_sys_mlockall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_mlockall(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813c29b0)
Location: mm/mlock.c:697
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff813c29b0-ffffffff813c2bab: __do_sys_mlockall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_mlockall(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813f7bf0)
Location: mm/mlock.c:704
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff813f7bf0-ffffffff813f7df7: __do_sys_mlockall (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_mlockall(int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff814237c0)
Location: mm/mlock.c:754
Inline: False
Direct callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
```
**Symbols:**

```
ffffffff814237c0-ffffffff814239c7: __do_sys_mlockall (STB_LOCAL)
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
In mm/mlock.c (ffff8000102feb6c)
Location: mm/mlock.c:799
Inline: True
Inline callers:
  - mm/mlock.c:__arm64_sys_mlockall
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
In mm/mlock.c (c051db74)
Location: mm/mlock.c:799
Inline: True
Inline callers:
  - mm/mlock.c:__se_sys_mlockall
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
In mm/mlock.c (c0000000003ca744)
Location: mm/mlock.c:799
Inline: True
Inline callers:
  - mm/mlock.c:__se_sys_mlockall
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
In mm/mlock.c (ffffffe00020ce38)
Location: mm/mlock.c:799
Inline: True
Inline callers:
  - mm/mlock.c:__se_sys_mlockall
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
In mm/mlock.c (ffffffff81260052)
Location: mm/mlock.c:799
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
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
In mm/mlock.c (ffffffff81252472)
Location: mm/mlock.c:799
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
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
In mm/mlock.c (ffffffff8125ddf2)
Location: mm/mlock.c:799
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
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
In mm/mlock.c (ffffffff8126d7d2)
Location: mm/mlock.c:799
Inline: True
Inline callers:
  - mm/mlock.c:__ia32_sys_mlockall
  - mm/mlock.c:__x64_sys_mlockall
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
