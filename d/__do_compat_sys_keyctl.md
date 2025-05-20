# Function: <code>__do_compat_sys_keyctl</code>

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
In security/keys/compat.c (ffffffff813eb529)
Location: security/keys/compat.c:59
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
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
In security/keys/compat.c (ffffffff8140604a)
Location: security/keys/compat.c:59
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
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
In security/keys/compat.c (ffffffff81433171)
Location: security/keys/compat.c:55
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
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
In security/keys/compat.c (ffffffff8144cee1)
Location: security/keys/compat.c:55
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat.c (ffffffff8149ed30)
Location: security/keys/compat.c:50
Inline: False
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8149ed30-ffffffff8149efa8: __do_compat_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat.c (ffffffff814bc760)
Location: security/keys/compat.c:17
Inline: False
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814bc760-ffffffff814bc9d8: __do_compat_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat.c (ffffffff814c2620)
Location: security/keys/compat.c:17
Inline: False
Direct callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff814c2620-ffffffff814c2898: __do_compat_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat.c (ffffffff8151b010)
Location: security/keys/compat.c:17
Inline: False
Direct callers:
  - security/keys/compat.c:__x64_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff8151b010-ffffffff8151b288: __do_compat_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat.c (ffffffff815adfb0)
Location: security/keys/compat.c:17
Inline: False
Direct callers:
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff815adfb0-ffffffff815ae435: __do_compat_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat.c (ffffffff816586c0)
Location: security/keys/compat.c:17
Inline: False
Direct callers:
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff816586c0-ffffffff81658b45: __do_compat_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat.c (ffffffff81690f40)
Location: security/keys/compat.c:17
Inline: False
Direct callers:
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff81690f40-ffffffff816913ed: __do_compat_sys_keyctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_compat_sys_keyctl(u32 option, u32 arg2, u32 arg3, u32 arg4, u32 arg5);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/keys/compat.c (ffffffff816cd510)
Location: security/keys/compat.c:17
Inline: False
Direct callers:
  - security/keys/compat.c:__ia32_compat_sys_keyctl
```
**Symbols:**

```
ffffffff816cd510-ffffffff816cd9bd: __do_compat_sys_keyctl (STB_LOCAL)
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
In security/keys/compat.c (ffff800010536eac)
Location: security/keys/compat.c:55
Inline: True
Inline callers:
  - security/keys/compat.c:__arm64_compat_sys_keyctl
```
</details>
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
In security/keys/compat.c (c0000000006858d4)
Location: security/keys/compat.c:55
Inline: True
Inline callers:
  - security/keys/compat.c:__se_compat_sys_keyctl
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
In security/keys/compat.c (ffffffff814454c1)
Location: security/keys/compat.c:55
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
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
In security/keys/compat.c (ffffffff81435f11)
Location: security/keys/compat.c:55
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
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
In security/keys/compat.c (ffffffff81441561)
Location: security/keys/compat.c:55
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
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
In security/keys/compat.c (ffffffff81458871)
Location: security/keys/compat.c:55
Inline: True
Inline callers:
  - security/keys/compat.c:__x32_compat_sys_keyctl
  - security/keys/compat.c:__ia32_compat_sys_keyctl
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
