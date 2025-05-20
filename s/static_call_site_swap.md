# Function: <code>static_call_site_swap</code>

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
void static_call_site_swap(void *_a, void *_b, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff81239750)
Location: kernel/static_call.c:81
Inline: False
```
**Symbols:**

```
ffffffff81239750-ffffffff81239783: static_call_site_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void static_call_site_swap(void *_a, void *_b, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff8123df40)
Location: kernel/static_call.c:81
Inline: False
```
**Symbols:**

```
ffffffff8123df40-ffffffff8123df73: static_call_site_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void static_call_site_swap(void *_a, void *_b, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call.c (ffffffff81278a00)
Location: kernel/static_call.c:81
Inline: False
```
**Symbols:**

```
ffffffff81278a00-ffffffff81278a33: static_call_site_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void static_call_site_swap(void *_a, void *_b, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff812cb840)
Location: kernel/static_call_inline.c:81
Inline: False
```
**Symbols:**

```
ffffffff812cb840-ffffffff812cb884: static_call_site_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void static_call_site_swap(void *_a, void *_b, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff813331b0)
Location: kernel/static_call_inline.c:92
Inline: False
```
**Symbols:**

```
ffffffff813331b0-ffffffff813331f4: static_call_site_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void static_call_site_swap(void *_a, void *_b, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff81363e80)
Location: kernel/static_call_inline.c:92
Inline: False
```
**Symbols:**

```
ffffffff81363e80-ffffffff81363ec4: static_call_site_swap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void static_call_site_swap(void *_a, void *_b, int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/static_call_inline.c (ffffffff8138cd50)
Location: kernel/static_call_inline.c:92
Inline: False
```
**Symbols:**

```
ffffffff8138cd50-ffffffff8138cd94: static_call_site_swap (STB_LOCAL)
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
