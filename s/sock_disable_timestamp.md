# Function: <code>sock_disable_timestamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817009e0)
Location: net/core/sock.c:436
Inline: False
Direct callers:
  - net/core/sock.c:sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff817009e0-ffffffff81700a16: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817673a0)
Location: net/core/sock.c:397
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff817673a0-ffffffff817673d7: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817943c0)
Location: net/core/sock.c:397
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff817943c0-ffffffff817943f7: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b27b0)
Location: net/core/sock.c:439
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff817b27b0-ffffffff817b27e4: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182a9a0)
Location: net/core/sock.c:429
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff8182a9a0-ffffffff8182a9d4: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81874b00)
Location: net/core/sock.c:435
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81874b00-ffffffff81874b33: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818953c0)
Location: net/core/sock.c:391
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff818953c0-ffffffff818953f3: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818df840)
Location: net/core/sock.c:440
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff818df840-ffffffff818df873: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81911a10)
Location: net/core/sock.c:440
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81911a10-ffffffff81911a43: sock_disable_timestamp (STB_LOCAL)
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
In net/core/sock.c (ffffffff819e62ba)
Location: net/core/sock.c:437
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
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
In net/core/sock.c (ffffffff819e5aca)
Location: net/core/sock.c:427
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
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
In net/core/sock.c (ffffffff819cbbda)
Location: net/core/sock.c:427
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
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
In net/core/sock.c (ffffffff81a7b23a)
Location: net/core/sock.c:446
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_set_timestamping
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
In net/core/sock.c (ffffffff81bef1ee)
Location: net/core/sock.c:465
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_set_timestamping
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
In net/core/sock.c (ffffffff81d9ba3e)
Location: net/core/sock.c:465
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_set_timestamping
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
In net/core/sock.c (ffffffff81e09c1a)
Location: net/core/sock.c:471
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_set_timestamping
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
In net/core/sock.c (ffffffff81ec660a)
Location: net/core/sock.c:468
Inline: True
Inline callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_set_timestamping
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
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffff800010ba9678)
Location: net/core/sock.c:440
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffff800010ba9678-ffff800010ba96d4: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c0cc7c14)
Location: net/core/sock.c:440
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
c0cc7c14-c0cc7c60: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (c000000000c7e820)
Location: net/core/sock.c:440
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
c000000000c7e820-c000000000c7e880: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffe00073caa4)
Location: net/core/sock.c:440
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffe00073caa4-ffffffe00073cafc: sock_disable_timestamp (STB_LOCAL)
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
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff818b1a10)
Location: net/core/sock.c:440
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff818b1a10-ffffffff818b1a43: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8186b960)
Location: net/core/sock.c:440
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff8186b960-ffffffff8186b993: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81902a10)
Location: net/core/sock.c:440
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff81902a10-ffffffff81902a43: sock_disable_timestamp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sock_disable_timestamp(struct sock *sk, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff819239b0)
Location: net/core/sock.c:440
Inline: False
Direct callers:
  - net/core/sock.c:__sk_destruct
  - net/core/sock.c:sock_setsockopt
```
**Symbols:**

```
ffffffff819239b0-ffffffff819239e3: sock_disable_timestamp (STB_LOCAL)
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
