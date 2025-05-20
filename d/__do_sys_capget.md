# Function: <code>__do_sys_capget</code>

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
In kernel/capability.c (ffffffff8109938c)
Location: kernel/capability.c:150
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
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
In kernel/capability.c (ffffffff810a170c)
Location: kernel/capability.c:150
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
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
In kernel/capability.c (ffffffff810a615c)
Location: kernel/capability.c:148
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
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
In kernel/capability.c (ffffffff810ac73c)
Location: kernel/capability.c:148
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b43d0)
Location: kernel/capability.c:148
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff810b43d0-ffffffff810b4552: __do_sys_capget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810af5a0)
Location: kernel/capability.c:148
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff810af5a0-ffffffff810af735: __do_sys_capget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b0b40)
Location: kernel/capability.c:148
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff810b0b40-ffffffff810b0cce: __do_sys_capget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810c28c0)
Location: kernel/capability.c:148
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff810c28c0-ffffffff810c2c83: __do_sys_capget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810d9da0)
Location: kernel/capability.c:148
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff810d9da0-ffffffff810da072: __do_sys_capget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810f9d50)
Location: kernel/capability.c:148
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff810f9d50-ffffffff810fa022: __do_sys_capget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81106060)
Location: kernel/capability.c:141
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff81106060-ffffffff81106246: __do_sys_capget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int __do_sys_capget(cap_user_header_t header, cap_user_data_t dataptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff8110f9b0)
Location: kernel/capability.c:141
Inline: False
Direct callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
```
**Symbols:**

```
ffffffff8110f9b0-ffffffff8110fb96: __do_sys_capget (STB_LOCAL)
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
In kernel/capability.c (ffff800010105f44)
Location: kernel/capability.c:148
Inline: True
Inline callers:
  - kernel/capability.c:__arm64_sys_capget
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
In kernel/capability.c (c0360fb0)
Location: kernel/capability.c:148
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capget
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
In kernel/capability.c (c00000000014d580)
Location: kernel/capability.c:148
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capget
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
In kernel/capability.c (ffffffe0000cb184)
Location: kernel/capability.c:148
Inline: True
Inline callers:
  - kernel/capability.c:__se_sys_capget
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
In kernel/capability.c (ffffffff810a6aac)
Location: kernel/capability.c:148
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
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
In kernel/capability.c (ffffffff8109548c)
Location: kernel/capability.c:148
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
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
In kernel/capability.c (ffffffff810a600c)
Location: kernel/capability.c:148
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
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
In kernel/capability.c (ffffffff810ae0cc)
Location: kernel/capability.c:148
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
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
