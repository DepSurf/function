# Function: <code>bpf_lsm_sctp_bind_connect</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_lsm_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81239410)
Location: include/linux/lsm_hook_defs.h:323
Inline: False
```
**Symbols:**

```
ffffffff81239410-ffffffff8123941d: bpf_lsm_sctp_bind_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123dc00)
Location: include/linux/lsm_hook_defs.h:333
Inline: False
```
**Symbols:**

```
ffffffff8123dc00-ffffffff8123dc0d: bpf_lsm_sctp_bind_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812786c0)
Location: include/linux/lsm_hook_defs.h:333
Inline: False
```
**Symbols:**

```
ffffffff812786c0-ffffffff812786cd: bpf_lsm_sctp_bind_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c8ec0)
Location: include/linux/lsm_hook_defs.h:332
Inline: False
```
**Symbols:**

```
ffffffff812c8ec0-ffffffff812c8ed1: bpf_lsm_sctp_bind_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132f850)
Location: include/linux/lsm_hook_defs.h:340
Inline: False
```
**Symbols:**

```
ffffffff8132f850-ffffffff8132f861: bpf_lsm_sctp_bind_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff813604c0)
Location: include/linux/lsm_hook_defs.h:341
Inline: False
```
**Symbols:**

```
ffffffff813604c0-ffffffff813604d1: bpf_lsm_sctp_bind_connect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_sctp_bind_connect(struct sock *sk, int optname, struct sockaddr *address, int addrlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81389370)
Location: include/linux/lsm_hook_defs.h:351
Inline: False
```
**Symbols:**

```
ffffffff81389370-ffffffff81389381: bpf_lsm_sctp_bind_connect (STB_GLOBAL)
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
