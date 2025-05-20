# Function: <code>__do_sys_keyctl</code>

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
In security/keys/keyctl.c (ffffffff813e8e89)
Location: security/keys/keyctl.c:1637
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
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
In security/keys/keyctl.c (ffffffff8140368e)
Location: security/keys/keyctl.c:1637
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
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
In security/keys/keyctl.c (ffffffff814302ad)
Location: security/keys/keyctl.c:1714
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
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
In security/keys/keyctl.c (ffffffff8144a00d)
Location: security/keys/keyctl.c:1714
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8149bc30)
Location: security/keys/keyctl.c:1869
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff8149bc30-ffffffff8149bf8a: __do_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814b96d0)
Location: security/keys/keyctl.c:1869
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff814b96d0-ffffffff814b9a2a: __do_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff814bf520)
Location: security/keys/keyctl.c:1869
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff814bf520-ffffffff814bf8b4: __do_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81517f40)
Location: security/keys/keyctl.c:1869
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff81517f40-ffffffff815182d4: __do_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff815aaa90)
Location: security/keys/keyctl.c:1869
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff815aaa90-ffffffff815aade7: __do_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff81654e10)
Location: security/keys/keyctl.c:1869
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff81654e10-ffffffff81655167: __do_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff8168d640)
Location: security/keys/keyctl.c:1874
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff8168d640-ffffffff8168d99d: __do_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_keyctl(int option, long unsigned int arg2, long unsigned int arg3, long unsigned int arg4, long unsigned int arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/keyctl.c (ffffffff816c9b90)
Location: security/keys/keyctl.c:1873
Inline: False
Direct callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
```
**Symbols:**

```
ffffffff816c9b90-ffffffff816c9eed: __do_sys_keyctl (STB_LOCAL)
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
In security/keys/keyctl.c (ffff800010533e2c)
Location: security/keys/keyctl.c:1714
Inline: True
Inline callers:
  - security/keys/keyctl.c:__arm64_sys_keyctl
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
In security/keys/keyctl.c (c06eb634)
Location: security/keys/keyctl.c:1714
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_keyctl
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
In security/keys/keyctl.c (c000000000681d24)
Location: security/keys/keyctl.c:1714
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_keyctl
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
In security/keys/keyctl.c (ffffffe000394152)
Location: security/keys/keyctl.c:1714
Inline: True
Inline callers:
  - security/keys/keyctl.c:__se_sys_keyctl
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
In security/keys/keyctl.c (ffffffff814425ed)
Location: security/keys/keyctl.c:1714
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
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
In security/keys/keyctl.c (ffffffff8143303d)
Location: security/keys/keyctl.c:1714
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
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
In security/keys/keyctl.c (ffffffff8143e78d)
Location: security/keys/keyctl.c:1714
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
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
In security/keys/keyctl.c (ffffffff8145593d)
Location: security/keys/keyctl.c:1714
Inline: True
Inline callers:
  - security/keys/keyctl.c:__ia32_sys_keyctl
  - security/keys/keyctl.c:__x64_sys_keyctl
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
