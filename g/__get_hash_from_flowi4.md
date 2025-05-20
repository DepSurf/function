# Function: <code>__get_hash_from_flowi4</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
__u32 __get_hash_from_flowi4(const struct flowi4 *fl4, struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81711b70)
Location: net/core/flow_dissector.c:822
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff81711b70-ffffffff81711be0: __get_hash_from_flowi4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
__u32 __get_hash_from_flowi4(const struct flowi4 *fl4, struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817794c0)
Location: net/core/flow_dissector.c:835
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff817794c0-ffffffff81779530: __get_hash_from_flowi4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
__u32 __get_hash_from_flowi4(const struct flowi4 *fl4, struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817a6610)
Location: net/core/flow_dissector.c:940
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_select_path
```
**Symbols:**

```
ffffffff817a6610-ffffffff817a6680: __get_hash_from_flowi4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
__u32 __get_hash_from_flowi4(const struct flowi4 *fl4, struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff817c4820)
Location: net/core/flow_dissector.c:1135
Inline: False
```
**Symbols:**

```
ffffffff817c4820-ffffffff817c4890: __get_hash_from_flowi4 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
__u32 __get_hash_from_flowi4(const struct flowi4 *fl4, struct flow_keys *keys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff8183e130)
Location: net/core/flow_dissector.c:1289
Inline: False
```
**Symbols:**

```
ffffffff8183e130-ffffffff8183e1a0: __get_hash_from_flowi4 (STB_GLOBAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
</ul>
