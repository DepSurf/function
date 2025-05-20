# Function: <code>sock_map_del_link</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f1ba1)
Location: net/core/sock_map.c:111
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81944043)
Location: net/core/sock_map.c:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81979033)
Location: net/core/sock_map.c:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sock_map_del_link(struct sock *sk, struct sk_psock *psock, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a4da60)
Location: net/core/sock_map.c:147
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_free
```
**Symbols:**

```
ffffffff81a4da60-ffffffff81a4db77: sock_map_del_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sock_map_del_link(struct sock *sk, struct sk_psock *psock, void *link_raw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81a53790)
Location: net/core/sock_map.c:139
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_hash_free
```
**Symbols:**

```
ffffffff81a53790-ffffffff81a538da: sock_map_del_link (STB_LOCAL)
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
In net/core/sock_map.c (ffffffff81a50006)
Location: net/core/sock_map.c:143
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
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
In net/core/sock_map.c (ffffffff81b08be8)
Location: net/core/sock_map.c:143
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
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
In net/core/sock_map.c (ffffffff81c8ec34)
Location: net/core/sock_map.c:143
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
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
In net/core/sock_map.c (ffffffff81e49db4)
Location: net/core/sock_map.c:143
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
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
In net/core/sock_map.c (ffffffff81ea5486)
Location: net/core/sock_map.c:139
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
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
In net/core/sock_map.c (ffffffff81f67f46)
Location: net/core/sock_map.c:139
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c1fd9c)
Location: net/core/sock_map.c:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d377fc)
Location: net/core/sock_map.c:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d11a2c)
Location: net/core/sock_map.c:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
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
In net/core/sock_map.c (ffffffe000798ee0)
Location: net/core/sock_map.c:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81918ea3)
Location: net/core/sock_map.c:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d2c53)
Location: net/core/sock_map.c:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8196a033)
Location: net/core/sock_map.c:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198c453)
Location: net/core/sock_map.c:106
Inline: True
Inline callers:
  - net/core/sock_map.c:sock_map_unref
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
