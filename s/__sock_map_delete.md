# Function: <code>__sock_map_delete</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sock_map_delete(struct bpf_stab *stab, struct sock *sk_test, struct sock **psk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f1cc0)
Location: net/core/sock_map.c:280
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_map_delete_elem
```
**Symbols:**

```
ffffffff818f1cc0-ffffffff818f1d25: __sock_map_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sock_map_delete(struct bpf_stab *stab, struct sock *sk_test, struct sock **psk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81944160)
Location: net/core/sock_map.c:277
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_map_delete_elem
```
**Symbols:**

```
ffffffff81944160-ffffffff819441c6: __sock_map_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sock_map_delete(struct bpf_stab *stab, struct sock *sk_test, struct sock **psk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81979150)
Location: net/core/sock_map.c:283
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_map_delete_elem
```
**Symbols:**

```
ffffffff81979150-ffffffff819791b6: __sock_map_delete (STB_LOCAL)
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
In net/core/sock_map.c (ffffffff81a4eaca)
Location: net/core/sock_map.c:409
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_delete_elem
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
In net/core/sock_map.c (ffffffff81a54aaa)
Location: net/core/sock_map.c:410
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_delete_elem
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
In net/core/sock_map.c (ffffffff81a506ca)
Location: net/core/sock_map.c:410
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_delete_elem
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
In net/core/sock_map.c (ffffffff81b09258)
Location: net/core/sock_map.c:410
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_delete_elem
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
In net/core/sock_map.c (ffffffff81c8f2e8)
Location: net/core/sock_map.c:410
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_delete_elem
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
In net/core/sock_map.c (ffffffff81e4a548)
Location: net/core/sock_map.c:412
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_delete_elem
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
In net/core/sock_map.c (ffffffff81ea5c54)
Location: net/core/sock_map.c:408
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_delete_elem
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
In net/core/sock_map.c (ffffffff81f68714)
Location: net/core/sock_map.c:408
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_delete_elem
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
int __sock_map_delete(struct bpf_stab *stab, struct sock *sk_test, struct sock **psk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c20138)
Location: net/core/sock_map.c:283
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_map_delete_elem
```
**Symbols:**

```
ffff800010c20138-ffff800010c2023c: __sock_map_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sock_map_delete(struct bpf_stab *stab, struct sock *sk_test, struct sock **psk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d378f4)
Location: net/core/sock_map.c:283
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_map_delete_elem
```
**Symbols:**

```
c0d378f4-c0d37980: __sock_map_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sock_map_delete(struct bpf_stab *stab, struct sock *sk_test, struct sock **psk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d11c10)
Location: net/core/sock_map.c:283
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_map_delete_elem
```
**Symbols:**

```
c000000000d11c10-c000000000d11d00: __sock_map_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe00079aa8a)
Location: net/core/sock_map.c:283
Inline: True
Inline callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_map_delete_elem
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
int __sock_map_delete(struct bpf_stab *stab, struct sock *sk_test, struct sock **psk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81918fc0)
Location: net/core/sock_map.c:283
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_map_delete_elem
```
**Symbols:**

```
ffffffff81918fc0-ffffffff81919026: __sock_map_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sock_map_delete(struct bpf_stab *stab, struct sock *sk_test, struct sock **psk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d2d70)
Location: net/core/sock_map.c:283
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_map_delete_elem
```
**Symbols:**

```
ffffffff818d2d70-ffffffff818d2dd6: __sock_map_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sock_map_delete(struct bpf_stab *stab, struct sock *sk_test, struct sock **psk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8196a150)
Location: net/core/sock_map.c:283
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_map_delete_elem
```
**Symbols:**

```
ffffffff8196a150-ffffffff8196a1b6: __sock_map_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sock_map_delete(struct bpf_stab *stab, struct sock *sk_test, struct sock **psk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198c570)
Location: net/core/sock_map.c:283
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_map_delete_elem
```
**Symbols:**

```
ffffffff8198c570-ffffffff8198c5d6: __sock_map_delete (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
