# Function: <code>__unix_insert_socket</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff817bdb80)
Location: net/unix/af_unix.c:253
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:unix_bind
```
**Symbols:**

```
ffffffff817bdb80-ffffffff817bdbd5: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8182aaf0)
Location: net/unix/af_unix.c:253
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff8182aaf0-ffffffff8182ab45: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8185c570)
Location: net/unix/af_unix.c:253
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff8185c570-ffffffff8185c5c5: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81880ab0)
Location: net/unix/af_unix.c:254
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff81880ab0-ffffffff81880ae8: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81901c40)
Location: net/unix/af_unix.c:254
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff81901c40-ffffffff81901c7e: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819586e0)
Location: net/unix/af_unix.c:254
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff819586e0-ffffffff8195871e: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198d2e0)
Location: net/unix/af_unix.c:256
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff8198d2e0-ffffffff8198d31e: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/unix/af_unix.c (0)
Location: net/unix/af_unix.c:253
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff819f8c50-ffffffff819f8c9b: __unix_insert_socket (STB_LOCAL)
ffffffff819fd5a2-ffffffff819fd5bd: __unix_insert_socket.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a2f8b0)
Location: net/unix/af_unix.c:253
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff81a2f8b0-ffffffff81a2f8ee: __unix_insert_socket (STB_LOCAL)
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
In net/unix/af_unix.c (ffffffff81b25e5f)
Location: net/unix/af_unix.c:259
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b32980)
Location: net/unix/af_unix.c:259
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff81b32980-ffffffff81b329f6: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81b204c0)
Location: net/unix/af_unix.c:259
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff81b204c0-ffffffff81b20536: __unix_insert_socket (STB_LOCAL)
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
In net/unix/af_unix.c (ffffffff81be937a)
Location: net/unix/af_unix.c:260
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __unix_insert_socket(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d800d6)
Location: net/unix/af_unix.c:303
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_bind_bsd
```
**Symbols:**

```
ffffffff81d7dbb0-ffffffff81d7dc64: __unix_insert_socket (STB_LOCAL)
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
In net/unix/af_unix.c (ffffffff81f4c28c)
Location: net/unix/af_unix.c:309
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:__unix_set_addr_hash
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
In net/unix/af_unix.c (ffffffff81fac06c)
Location: net/unix/af_unix.c:322
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:__unix_set_addr_hash
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
In net/unix/af_unix.c (ffffffff8207948c)
Location: net/unix/af_unix.c:321
Inline: True
Inline callers:
  - net/unix/af_unix.c:unix_create1
  - net/unix/af_unix.c:__unix_set_addr_hash
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
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffff800010ceea78)
Location: net/unix/af_unix.c:253
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffff800010ceea78-ffff800010ceead4: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c0df6fd8)
Location: net/unix/af_unix.c:253
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
c0df6fd8-c0df7044: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (c000000000e13bd0)
Location: net/unix/af_unix.c:253
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
c000000000e13bd0-c000000000e13c20: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffe00083bb34)
Location: net/unix/af_unix.c:253
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_autobind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffe00083bb34-ffffffe00083bb82: __unix_insert_socket (STB_LOCAL)
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
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff819cef40)
Location: net/unix/af_unix.c:253
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff819cef40-ffffffff819cef7e: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8198bd00)
Location: net/unix/af_unix.c:253
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff8198bd00-ffffffff8198bd3e: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a399c0)
Location: net/unix/af_unix.c:253
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff81a399c0-ffffffff81a399fe: __unix_insert_socket (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __unix_insert_socket(struct hlist_head *list, struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81a457d0)
Location: net/unix/af_unix.c:253
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_bind
  - net/unix/af_unix.c:unix_create1
```
**Symbols:**

```
ffffffff81a457d0-ffffffff81a4580e: __unix_insert_socket (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
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
