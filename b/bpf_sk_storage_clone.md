# Function: <code>bpf_sk_storage_clone</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81989be0)
Location: net/core/bpf_sk_storage.c:773
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81989be0-ffffffff81989d88: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a61f70)
Location: net/core/bpf_sk_storage.c:777
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81a61f70-ffffffff81a6214e: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a6a450)
Location: net/core/bpf_sk_storage.c:187
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81a6a450-ffffffff81a6a5cb: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81a52bb0)
Location: net/core/bpf_sk_storage.c:187
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81a52bb0-ffffffff81a52d2b: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81b0b880)
Location: net/core/bpf_sk_storage.c:187
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81b0b880-ffffffff81b0b9f3: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81c92060)
Location: net/core/bpf_sk_storage.c:189
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81c92060-ffffffff81c921f5: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81e4d630)
Location: net/core/bpf_sk_storage.c:160
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81e4d630-ffffffff81e4d7e1: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81ea8c80)
Location: net/core/bpf_sk_storage.c:154
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81ea8c80-ffffffff81ea8e3f: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81f6b740)
Location: net/core/bpf_sk_storage.c:154
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81f6b740-ffffffff81f6b8ff: bpf_sk_storage_clone (STB_GLOBAL)
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
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffff800010c32280)
Location: net/core/bpf_sk_storage.c:773
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffff800010c32280-ffff800010c32430: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c0d48cec)
Location: net/core/bpf_sk_storage.c:773
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
c0d48cec-c0d48e8c: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (c000000000d2b590)
Location: net/core/bpf_sk_storage.c:773
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
c000000000d2b590-c000000000d2b7e4: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffe0007a7c1a)
Location: net/core/bpf_sk_storage.c:773
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffe0007a7c1a-ffffffe0007a7d6a: bpf_sk_storage_clone (STB_GLOBAL)
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
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff81929a50)
Location: net/core/bpf_sk_storage.c:773
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff81929a50-ffffffff81929bf8: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff818e3800)
Location: net/core/bpf_sk_storage.c:773
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff818e3800-ffffffff818e39a8: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8197abe0)
Location: net/core/bpf_sk_storage.c:773
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff8197abe0-ffffffff8197ad88: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_sk_storage_clone(const struct sock *sk, struct sock *newsk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/bpf_sk_storage.c (ffffffff8199d130)
Location: net/core/bpf_sk_storage.c:773
Inline: False
Direct callers:
  - net/core/sock.c:sk_clone_lock
```
**Symbols:**

```
ffffffff8199d130-ffffffff8199d2de: bpf_sk_storage_clone (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
