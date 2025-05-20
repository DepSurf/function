# Function: <code>__se_sys_capget</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b4585)
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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810af765)
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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810b0cf5)
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
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810c2cb5)
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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810da0a5)
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
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff810fa075)
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
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffff81106295)
Location: kernel/capability.c:141
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
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
In kernel/capability.c (ffffffff8110fbe5)
Location: kernel/capability.c:141
Inline: True
Inline callers:
  - kernel/capability.c:__ia32_sys_capget
  - kernel/capability.c:__x64_sys_capget
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
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_capget(long int header, long int dataptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c0360f7c)
Location: kernel/capability.c:148
Inline: False
```
**Symbols:**

```
c0360f7c-c03611d4: __se_sys_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_capget(long int header, long int dataptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (c00000000014d540)
Location: kernel/capability.c:148
Inline: False
```
**Symbols:**

```
c00000000014d540-c00000000014d798: __se_sys_capget (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_capget(long int header, long int dataptr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/capability.c (ffffffe0000cb168)
Location: kernel/capability.c:148
Inline: False
```
**Symbols:**

```
ffffffe0000cb168-ffffffe0000cb2da: __se_sys_capget (STB_GLOBAL)
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
<b>Arch</b>
<ul>
</ul>
