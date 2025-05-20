# Function: <code>unix_mkname</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff817be580)
Location: net/unix/af_unix.c:225
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_sendmsg
```
**Symbols:**

```
ffffffff817be580-ffffffff817be5fa: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8182b520)
Location: net/unix/af_unix.c:225
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8182b520-ffffffff8182b59a: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8185cf40)
Location: net/unix/af_unix.c:225
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8185cf40-ffffffff8185cfba: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81881750)
Location: net/unix/af_unix.c:226
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81881750-ffffffff818817cb: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819028f0)
Location: net/unix/af_unix.c:226
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff819028f0-ffffffff8190296b: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81958d60)
Location: net/unix/af_unix.c:226
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81958d60-ffffffff81958ddb: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198d910)
Location: net/unix/af_unix.c:226
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8198d910-ffffffff8198d991: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819f8fc0)
Location: net/unix/af_unix.c:223
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff819f8fc0-ffffffff819f9041: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a2fc10)
Location: net/unix/af_unix.c:223
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81a2fc10-ffffffff81a2fc91: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b237d0)
Location: net/unix/af_unix.c:229
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81b237d0-ffffffff81b23851: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b321a0)
Location: net/unix/af_unix.c:229
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81b321a0-ffffffff81b32221: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b1fec0)
Location: net/unix/af_unix.c:229
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81b1fec0-ffffffff81b1ff41: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81be4c20)
Location: net/unix/af_unix.c:230
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81be4c20-ffffffff81be4ca1: unix_mkname (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffff800010cef1e0)
Location: net/unix/af_unix.c:223
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffff800010cef1e0-ffff800010cef298: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c0df6eb4)
Location: net/unix/af_unix.c:223
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c0df6eb4-c0df6f48: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c000000000e14ec0)
Location: net/unix/af_unix.c:223
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
c000000000e14ec0-c000000000e14fa8: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffe00083c1ea)
Location: net/unix/af_unix.c:223
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffe00083c1ea-ffffffe00083c2a4: unix_mkname (STB_LOCAL)
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
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819cf2a0)
Location: net/unix/af_unix.c:223
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff819cf2a0-ffffffff819cf321: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198c060)
Location: net/unix/af_unix.c:223
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff8198c060-ffffffff8198c0e1: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a39d20)
Location: net/unix/af_unix.c:223
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81a39d20-ffffffff81a39da1: unix_mkname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int unix_mkname(struct sockaddr_un *sunaddr, int len, unsigned int *hashp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a46360)
Location: net/unix/af_unix.c:223
Inline: True
Direct callers:
  - net/unix/af_unix.c:unix_dgram_sendmsg
  - net/unix/af_unix.c:unix_stream_connect
  - net/unix/af_unix.c:unix_dgram_connect
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff81a46360-ffffffff81a463e1: unix_mkname (STB_LOCAL)
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
