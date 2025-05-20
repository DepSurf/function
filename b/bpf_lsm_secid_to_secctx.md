# Function: <code>bpf_lsm_secid_to_secctx</code>

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
int bpf_lsm_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81239120)
Location: include/linux/lsm_hook_defs.h:251
Inline: False
```
**Symbols:**

```
ffffffff81239120-ffffffff81239130: bpf_lsm_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lsm_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123d910)
Location: include/linux/lsm_hook_defs.h:261
Inline: False
```
**Symbols:**

```
ffffffff8123d910-ffffffff8123d920: bpf_lsm_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lsm_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812783d0)
Location: include/linux/lsm_hook_defs.h:261
Inline: False
```
**Symbols:**

```
ffffffff812783d0-ffffffff812783e0: bpf_lsm_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lsm_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c89a0)
Location: include/linux/lsm_hook_defs.h:260
Inline: False
```
**Symbols:**

```
ffffffff812c89a0-ffffffff812c89b4: bpf_lsm_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lsm_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132f040)
Location: include/linux/lsm_hook_defs.h:268
Inline: False
```
**Symbols:**

```
ffffffff8132f040-ffffffff8132f054: bpf_lsm_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lsm_secid_to_secctx(u32 secid, char **secdata, u32 *seclen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8135fcb0)
Location: include/linux/lsm_hook_defs.h:269
Inline: False
```
**Symbols:**

```
ffffffff8135fcb0-ffffffff8135fcc4: bpf_lsm_secid_to_secctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lsm_secid_to_secctx(u32 secid, struct lsmcontext *cp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81388b30)
Location: include/linux/lsm_hook_defs.h:278
Inline: False
```
**Symbols:**

```
ffffffff81388b30-ffffffff81388b44: bpf_lsm_secid_to_secctx (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct lsmcontext *cp</code>
</li>
<li>
<b>Param removed. </b>
<code>char **secdata</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 *seclen</code>
</li>
</ul>
</details>
</li>
</ul>
