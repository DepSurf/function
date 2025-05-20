# Function: <code>compat_sock_get_timestampns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff8173e4a0)
Location: net/compat.c:458
Inline: False
```
**Symbols:**

```
ffffffff8173e4a0-ffffffff8173e54a: compat_sock_get_timestampns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817ab1b0)
Location: net/compat.c:472
Inline: False
```
**Symbols:**

```
ffffffff817ab1b0-ffffffff817ab259: compat_sock_get_timestampns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817da7d0)
Location: net/compat.c:472
Inline: False
```
**Symbols:**

```
ffffffff817da7d0-ffffffff817da879: compat_sock_get_timestampns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int compat_sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff817f9d00)
Location: net/compat.c:471
Inline: False
```
**Symbols:**

```
ffffffff817f9d00-ffffffff817f9daf: compat_sock_get_timestampns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int compat_sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff81877610)
Location: net/compat.c:478
Inline: False
```
**Symbols:**

```
ffffffff81877610-ffffffff818776bf: compat_sock_get_timestampns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int compat_sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818c8d10)
Location: net/compat.c:486
Inline: False
```
**Symbols:**

```
ffffffff818c8d10-ffffffff818c8db9: compat_sock_get_timestampns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int compat_sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/compat.c (ffffffff818f3ed0)
Location: net/compat.c:491
Inline: True
```
**Symbols:**

```
ffffffff818f3ed0-ffffffff818f3f6f: compat_sock_get_timestampns (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
