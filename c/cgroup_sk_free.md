# Function: <code>cgroup_sk_free</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81121800)
Location: kernel/cgroup.c:6316
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffff81121800-ffffffff81121846: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup.c (ffffffff81129da0)
Location: kernel/cgroup.c:6345
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffff81129da0-ffffffff81129de6: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81128b80)
Location: kernel/cgroup/cgroup.c:5170
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffff81128b80-ffffffff81128bc6: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811351b0)
Location: kernel/cgroup/cgroup.c:5837
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffff811351b0-ffffffff811351fd: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811438d0)
Location: kernel/cgroup/cgroup.c:5875
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffff811438d0-ffffffff8114391c: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114f3e0)
Location: kernel/cgroup/cgroup.c:5978
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffff8114f3e0-ffffffff8114f42c: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115b270)
Location: kernel/cgroup/cgroup.c:6399
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffff8115b270-ffffffff8115b2ed: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81166f30)
Location: kernel/cgroup/cgroup.c:6418
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffff81166f30-ffffffff81166fad: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81178640)
Location: kernel/cgroup/cgroup.c:6483
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffff81178640-ffffffff811786c8: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811753f0)
Location: kernel/cgroup/cgroup.c:6475
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
**Symbols:**

```
ffffffff811753f0-ffffffff81175490: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175f60)
Location: kernel/cgroup/cgroup.c:6453
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
**Symbols:**

```
ffffffff81175f60-ffffffff81176000: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8119d530)
Location: kernel/cgroup/cgroup.c:6678
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
**Symbols:**

```
ffffffff8119d530-ffffffff8119d5b9: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811cd870)
Location: kernel/cgroup/cgroup.c:6712
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
**Symbols:**

```
ffffffff811cd870-ffffffff811cd913: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81210f20)
Location: kernel/cgroup/cgroup.c:6979
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
**Symbols:**

```
ffffffff81210f20-ffffffff81210fc3: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81226910)
Location: kernel/cgroup/cgroup.c:6960
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
**Symbols:**

```
ffffffff81226910-ffffffff812269b3: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8123e5a0)
Location: kernel/cgroup/cgroup.c:7001
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
**Symbols:**

```
ffffffff8123e5a0-ffffffff8123e643: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d8e28)
Location: kernel/cgroup/cgroup.c:6418
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffff8000101d8e28-ffff8000101d8ea0: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c041bc58)
Location: kernel/cgroup/cgroup.c:6418
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
c041bc58-c041bd60: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c0000000002462b0)
Location: kernel/cgroup/cgroup.c:6418
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
c0000000002462b0-c00000000024641c: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe000151da6)
Location: kernel/cgroup/cgroup.c:6418
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffe000151da6-ffffffe000151e8e: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115f550)
Location: kernel/cgroup/cgroup.c:6418
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffff8115f550-ffffffff8115f5cd: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811527e0)
Location: kernel/cgroup/cgroup.c:6418
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffff811527e0-ffffffff8115285d: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115d320)
Location: kernel/cgroup/cgroup.c:6418
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffff8115d320-ffffffff8115d39d: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cgroup_sk_free(struct sock_cgroup_data *skcd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8116a520)
Location: kernel/cgroup/cgroup.c:6418
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
```
**Symbols:**

```
ffffffff8116a520-ffffffff8116a5c8: cgroup_sk_free (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
