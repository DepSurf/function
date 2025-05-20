# Function: <code>tcp_default_init_rwnd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u32 tcp_default_init_rwnd(u32 mss);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817743c2)
Location: net/ipv4/tcp_output.c:187
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
**Symbols:**

```
ffffffff81775300-ffffffff8177532e: tcp_default_init_rwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
u32 tcp_default_init_rwnd(u32 mss);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e1258)
Location: net/ipv4/tcp_output.c:184
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
**Symbols:**

```
ffffffff817e2230-ffffffff817e225e: tcp_default_init_rwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
u32 tcp_default_init_rwnd(u32 mss);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81811678)
Location: net/ipv4/tcp_output.c:184
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
**Symbols:**

```
ffffffff81812870-ffffffff8181289e: tcp_default_init_rwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
u32 tcp_default_init_rwnd(u32 mss);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81831788)
Location: net/ipv4/tcp_output.c:185
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
**Symbols:**

```
ffffffff81832a10-ffffffff81832a3c: tcp_default_init_rwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
u32 tcp_default_init_rwnd(u32 mss);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b0b95)
Location: net/ipv4/tcp_output.c:170
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
**Symbols:**

```
ffffffff818b1e20-ffffffff818b1e4c: tcp_default_init_rwnd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
u32 tcp_default_init_rwnd(u32 mss);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8190631a)
Location: net/ipv4/tcp_output.c:183
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_select_initial_window
Direct callers:
  - net/ipv4/tcp_input.c:tcp_init_buffer_space
```
**Symbols:**

```
ffffffff819074b0-ffffffff819074dc: tcp_default_init_rwnd (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
