# Function: <code>__se_sys_poll</code>

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
In fs/select.c (ffffffff812b2d87)
Location: fs/select.c:1013
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff812c7ea7)
Location: fs/select.c:1052
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff812e4a57)
Location: fs/select.c:1047
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff812f6477)
Location: fs/select.c:1047
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff8132fa67)
Location: fs/select.c:1057
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff8133b397)
Location: fs/select.c:1064
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff81341869)
Location: fs/select.c:1064
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff8138f229)
Location: fs/select.c:1067
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff81410369)
Location: fs/select.c:1068
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff8149b019)
Location: fs/select.c:1068
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff814d00c9)
Location: fs/select.c:1068
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff81502a09)
Location: fs/select.c:1068
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffff8000103a3768)
Location: fs/select.c:1047
Inline: True
Inline callers:
  - fs/select.c:__arm64_sys_poll
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_poll(long int ufds, long int nfds, long int timeout_msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c05869bc)
Location: fs/select.c:1047
Inline: False
```
**Symbols:**

```
c05869bc-c0586b10: __se_sys_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_poll(long int ufds, long int nfds, long int timeout_msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c00000000049d520)
Location: fs/select.c:1047
Inline: False
```
**Symbols:**

```
c00000000049d520-c00000000049d680: __se_sys_poll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int __se_sys_poll(long int ufds, long int nfds, long int timeout_msecs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffe00026b94c)
Location: fs/select.c:1047
Inline: False
```
**Symbols:**

```
ffffffe00026b94c-ffffffe00026ba48: __se_sys_poll (STB_GLOBAL)
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
In fs/select.c (ffffffff812eea57)
Location: fs/select.c:1047
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff812df687)
Location: fs/select.c:1047
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff812ec867)
Location: fs/select.c:1047
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
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
In fs/select.c (ffffffff812fd867)
Location: fs/select.c:1047
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_poll
  - fs/select.c:__x64_sys_poll
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
