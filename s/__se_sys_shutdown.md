# Function: <code>__se_sys_shutdown</code>

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
In net/socket.c (ffffffff81873655)
Location: net/socket.c:1984
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff81893fa5)
Location: net/socket.c:1971
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff818de2c5)
Location: net/socket.c:2166
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff81910325)
Location: net/socket.c:2166
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff819e1cc5)
Location: net/socket.c:2209
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff819e1965)
Location: net/socket.c:2202
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff819c7a05)
Location: net/socket.c:2196
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff81a76d55)
Location: net/socket.c:2269
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff81be9f75)
Location: net/socket.c:2344
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff81d96895)
Location: net/socket.c:2336
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff81e04ee5)
Location: net/socket.c:2373
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff81ec17a5)
Location: net/socket.c:2443
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffff800010ba8378)
Location: net/socket.c:2166
Inline: True
Inline callers:
  - net/socket.c:__arm64_sys_shutdown
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_shutdown(long int fd, long int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c0cc6fb8)
Location: net/socket.c:2166
Inline: False
```
**Symbols:**

```
c0cc6fb8-c0cc6fd4: __se_sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_shutdown(long int fd, long int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (c000000000c7cb10)
Location: net/socket.c:2166
Inline: False
```
**Symbols:**

```
c000000000c7cb10-c000000000c7cb48: __se_sys_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_shutdown(long int fd, long int how);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/socket.c (ffffffe00073bd42)
Location: net/socket.c:2166
Inline: False
```
**Symbols:**

```
ffffffe00073bd42-ffffffe00073bd78: __se_sys_shutdown (STB_GLOBAL)
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
In net/socket.c (ffffffff818b0325)
Location: net/socket.c:2166
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff8186a275)
Location: net/socket.c:2166
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff81901325)
Location: net/socket.c:2166
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
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
In net/socket.c (ffffffff81922315)
Location: net/socket.c:2166
Inline: True
Inline callers:
  - net/socket.c:__ia32_sys_shutdown
  - net/socket.c:__x64_sys_shutdown
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
