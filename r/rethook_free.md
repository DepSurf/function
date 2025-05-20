# Function: <code>rethook_free</code>

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
void rethook_free(struct rethook *rh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff81269070)
Location: kernel/trace/rethook.c:66
Inline: False
Direct callers:
  - kernel/trace/fprobe.c:unregister_fprobe
  - kernel/trace/fprobe.c:register_fprobe_ips
  - kernel/trace/fprobe.c:register_fprobe
  - kernel/trace/fprobe.c:fprobe_init_rethook
```
**Symbols:**

```
ffffffff81269070-ffffffff81269096: rethook_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rethook_free(struct rethook *rh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812bb3a0)
Location: kernel/trace/rethook.c:66
Inline: False
Direct callers:
  - kernel/trace/fprobe.c:unregister_fprobe
  - kernel/trace/fprobe.c:register_fprobe_ips
  - kernel/trace/fprobe.c:register_fprobe
  - kernel/trace/fprobe.c:fprobe_init_rethook
```
**Symbols:**

```
ffffffff812bb3a0-ffffffff812bb3c6: rethook_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rethook_free(struct rethook *rh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812defc0)
Location: kernel/trace/rethook.c:79
Inline: False
Direct callers:
  - kernel/trace/fprobe.c:register_fprobe_ips
  - kernel/trace/fprobe.c:register_fprobe
  - kernel/trace/fprobe.c:fprobe_init_rethook
```
**Symbols:**

```
ffffffff812defc0-ffffffff812defe6: rethook_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rethook_free(struct rethook *rh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/rethook.c (ffffffff812fcef0)
Location: kernel/trace/rethook.c:64
Inline: False
Direct callers:
  - kernel/trace/fprobe.c:register_fprobe_ips
  - kernel/trace/fprobe.c:register_fprobe
```
**Symbols:**

```
ffffffff812fcef0-ffffffff812fcf16: rethook_free (STB_GLOBAL)
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
