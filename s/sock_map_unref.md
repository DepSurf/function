# Function: <code>sock_map_unref</code>

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
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f1b70)
Location: net/core/sock_map.c:137
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff818f1b70-ffffffff818f1cb2: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81944010)
Location: net/core/sock_map.c:132
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff81944010-ffffffff81944152: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81979000)
Location: net/core/sock_map.c:132
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff81979000-ffffffff81979142: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4e64e)
Location: net/core/sock_map.c:173
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_delete_elem
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff81a4e780-ffffffff81a4e7ef: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a5462e)
Location: net/core/sock_map.c:170
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_hash_free
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_delete_elem
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff81a54760-ffffffff81a547cf: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4ffd0)
Location: net/core/sock_map.c:176
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_delete_elem
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff81a4ffd0-ffffffff81a50184: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81b08bb0)
Location: net/core/sock_map.c:179
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_delete_elem
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff81b08bb0-ffffffff81b08d8b: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81c8ebe0)
Location: net/core/sock_map.c:179
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_delete_elem
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff81c8ebe0-ffffffff81c8ede5: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81e49d60)
Location: net/core/sock_map.c:179
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_delete_elem
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff81e49d60-ffffffff81e49f65: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81ea5430)
Location: net/core/sock_map.c:175
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_delete_elem
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff81ea5430-ffffffff81ea5673: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81f67ef0)
Location: net/core/sock_map.c:175
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_map_remove_links
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_delete_elem
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff81f67ef0-ffffffff81f68133: sock_map_unref (STB_LOCAL)
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
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c1fd68)
Location: net/core/sock_map.c:132
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffff800010c1fd68-ffff800010c1ff9c: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d377d4)
Location: net/core/sock_map.c:132
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
c0d377d4-c0d378f4: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d119e0)
Location: net/core/sock_map.c:132
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
c000000000d119e0-c000000000d11c10: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe000798eb2)
Location: net/core/sock_map.c:132
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:sock_map_delete_elem
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffe000798eb2-ffffffe000798fd8: sock_map_unref (STB_LOCAL)
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
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81918e70)
Location: net/core/sock_map.c:132
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff81918e70-ffffffff81918fb2: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d2c20)
Location: net/core/sock_map.c:132
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff818d2c20-ffffffff818d2d62: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8196a000)
Location: net/core/sock_map.c:132
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff8196a000-ffffffff8196a142: sock_map_unref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sock_map_unref(struct sock *sk, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198c420)
Location: net/core/sock_map.c:132
Inline: False
Direct callers:
  - net/core/sock_map.c:sk_psock_unlink
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_free
  - net/core/sock_map.c:sock_hash_update_common
  - net/core/sock_map.c:sock_hash_delete_elem
  - net/core/sock_map.c:sock_map_update_common
  - net/core/sock_map.c:__sock_map_delete
  - net/core/sock_map.c:sock_map_free
```
**Symbols:**

```
ffffffff8198c420-ffffffff8198c562: sock_map_unref (STB_LOCAL)
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
