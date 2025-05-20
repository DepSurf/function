# Function: <code>__se_sys_capset</code>

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
In kernel/capability.c (ffffffff8109951c)
Location: kernel/capability.c:224
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff810a189c)
Location: kernel/capability.c:224
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff810a62ec)
Location: kernel/capability.c:222
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff810ac8cc)
Location: kernel/capability.c:222
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff810b4785)
Location: kernel/capability.c:222
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff810af975)
Location: kernel/capability.c:222
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff810b0f35)
Location: kernel/capability.c:222
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff810c3025)
Location: kernel/capability.c:222
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff810da455)
Location: kernel/capability.c:222
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff810fa455)
Location: kernel/capability.c:222
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff811064f5)
Location: kernel/capability.c:220
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff8110fe45)
Location: kernel/capability.c:220
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffff80001010630c)
Location: kernel/capability.c:222
Inline: True
Inline callers:
  - kernel/capability.c:__arm64_sys_capset
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_capset(long int header, long int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c03611d4)
Location: kernel/capability.c:222
Inline: False
```
**Symbols:**

```
c03611d4-c0361440: __se_sys_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_capset(long int header, long int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c00000000014d7a0)
Location: kernel/capability.c:222
Inline: False
```
**Symbols:**

```
c00000000014d7a0-c00000000014da6c: __se_sys_capset (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_capset(long int header, long int data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffe0000cb2da)
Location: kernel/capability.c:222
Inline: False
```
**Symbols:**

```
ffffffe0000cb2da-ffffffe0000cb46c: __se_sys_capset (STB_GLOBAL)
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
In kernel/capability.c (ffffffff810a6c3c)
Location: kernel/capability.c:222
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff8109561c)
Location: kernel/capability.c:222
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff810a619c)
Location: kernel/capability.c:222
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
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
In kernel/capability.c (ffffffff810ae27c)
Location: kernel/capability.c:222
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capset
  - kernel/capability.c:__x64_sys_capset
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
