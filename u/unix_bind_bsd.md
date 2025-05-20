# Function: <code>unix_bind_bsd</code>

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
In <code>4.18</code>: Absent ⚠️
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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unix_bind_bsd(struct sock *sk, struct unix_address *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81be6ce0)
Location: net/unix/af_unix.c:1067
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81be6ce0-ffffffff81be6e85: unix_bind_bsd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unix_bind_bsd(struct sock *sk, struct sockaddr_un *sunaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d7df30)
Location: net/unix/af_unix.c:1134
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81d7df30-ffffffff81d7e298: unix_bind_bsd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unix_bind_bsd(struct sock *sk, struct sockaddr_un *sunaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f4c900)
Location: net/unix/af_unix.c:1185
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81f4c900-ffffffff81f4ccf0: unix_bind_bsd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unix_bind_bsd(struct sock *sk, struct sockaddr_un *sunaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81fac270)
Location: net/unix/af_unix.c:1209
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81fac270-ffffffff81fac665: unix_bind_bsd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unix_bind_bsd(struct sock *sk, struct sockaddr_un *sunaddr, int addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff82079690)
Location: net/unix/af_unix.c:1195
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff82079690-ffffffff82079a85: unix_bind_bsd (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sockaddr_un *sunaddr</code>
</li>
<li>
<b>Param added. </b>
<code>int addr_len</code>
</li>
<li>
<b>Param removed. </b>
<code>struct unix_address *addr</code>
</li>
</ul>
</details>
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
