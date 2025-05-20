# Function: <code>audit_unix_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81390360)
Location: security/apparmor/net.c:74
Inline: False
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81390360-ffffffff81390438: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813cb910)
Location: security/apparmor/net.c:74
Inline: False
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff813cb910-ffffffff813cb9e8: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813e2f90)
Location: security/apparmor/net.c:74
Inline: False
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff813e2f90-ffffffff813e3068: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff813f1430)
Location: security/apparmor/net.c:74
Inline: False
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff813f1430-ffffffff813f1508: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81419450)
Location: security/apparmor/net.c:74
Inline: False
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81419450-ffffffff81419528: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8144b880)
Location: security/apparmor/net.c:79
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8144b880-ffffffff8144b958: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814687f0)
Location: security/apparmor/net.c:79
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814687f0-ffffffff814688c8: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81495820)
Location: security/apparmor/net.c:75
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81495820-ffffffff81495903: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814af750)
Location: security/apparmor/net.c:75
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814af750-ffffffff814af833: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8150ebb0)
Location: security/apparmor/net.c:76
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8150ebb0-ffffffff8150ec93: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8152ba20)
Location: security/apparmor/net.c:76
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8152ba20-ffffffff8152bb03: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81531cc0)
Location: security/apparmor/net.c:76
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81531cc0-ffffffff81531da3: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81590110)
Location: security/apparmor/net.c:76
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81590110-ffffffff815901f3: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81631140)
Location: security/apparmor/net.c:76
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81631140-ffffffff81631242: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff816e5e90)
Location: security/apparmor/net.c:76
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff816e5e90-ffffffff816e5f92: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8171f590)
Location: security/apparmor/net.c:76
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8171f590-ffffffff8171f692: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff8175dfc0)
Location: security/apparmor/net.c:78
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff8175dfc0-ffffffff8175e0c2: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffff8000105a6e18)
Location: security/apparmor/net.c:75
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffff8000105a6e18-ffff8000105a6f28: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (c0756e4c)
Location: security/apparmor/net.c:75
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
c0756e4c-c0756f1c: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (c00000000072373c)
Location: security/apparmor/net.c:75
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_unix_sk_addr
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_unix_sk_addr
```
**Symbols:**

```
c000000000723580-c0000000007236e4: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffe0003f0856)
Location: security/apparmor/net.c:75
Inline: True
Inline callers:
  - security/apparmor/net.c:audit_unix_sk_addr
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_unix_sk_addr
```
**Symbols:**

```
ffffffe0003f071c-ffffffe0003f0812: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814a7d30)
Location: security/apparmor/net.c:75
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814a7d30-ffffffff814a7e13: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff81498750)
Location: security/apparmor/net.c:75
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff81498750-ffffffff81498833: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814a3dd0)
Location: security/apparmor/net.c:75
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814a3dd0-ffffffff814a3eb3: audit_unix_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void audit_unix_addr(struct audit_buffer *ab, const char *str, struct sockaddr_un *addr, int addrlen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/net.c (ffffffff814bc660)
Location: security/apparmor/net.c:75
Inline: True
Direct callers:
  - security/apparmor/net.c:audit_net_cb
  - security/apparmor/net.c:audit_net_cb
```
**Symbols:**

```
ffffffff814bc660-ffffffff814bc743: audit_unix_addr (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
