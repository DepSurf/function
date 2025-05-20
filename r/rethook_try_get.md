# Function: <code>rethook_try_get</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct rethook_node *rethook_try_get(struct rethook *rh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff81268c40)
Location: kernel/trace/rethook.c:146
Inline: False
Direct callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
**Symbols:**

```
ffffffff81268c40-ffffffff81268d17: rethook_try_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rethook_node *rethook_try_get(struct rethook *rh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812baf00)
Location: kernel/trace/rethook.c:148
Inline: False
Direct callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
**Symbols:**

```
ffffffff812baf00-ffffffff812bafd7: rethook_try_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rethook_node *rethook_try_get(struct rethook *rh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812deb00)
Location: kernel/trace/rethook.c:161
Inline: False
Direct callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
**Symbols:**

```
ffffffff812deb00-ffffffff812debd7: rethook_try_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rethook_node *rethook_try_get(struct rethook *rh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812fcca0)
Location: kernel/trace/rethook.c:161
Inline: False
Direct callers:
  - kernel/kprobes.c:pre_handler_kretprobe
```
**Symbols:**

```
ffffffff812fcca0-ffffffff812fcce6: rethook_try_get (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
