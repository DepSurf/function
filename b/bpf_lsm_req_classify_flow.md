# Function: <code>bpf_lsm_req_classify_flow</code>

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
void bpf_lsm_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81239390)
Location: include/linux/lsm_hook_defs.h:313
Inline: False
```
**Symbols:**

```
ffffffff81239390-ffffffff8123939b: bpf_lsm_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_lsm_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8123db80)
Location: include/linux/lsm_hook_defs.h:323
Inline: False
```
**Symbols:**

```
ffffffff8123db80-ffffffff8123db8b: bpf_lsm_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_lsm_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81278640)
Location: include/linux/lsm_hook_defs.h:323
Inline: False
```
**Symbols:**

```
ffffffff81278640-ffffffff8127864b: bpf_lsm_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_lsm_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff812c8de0)
Location: include/linux/lsm_hook_defs.h:322
Inline: False
```
**Symbols:**

```
ffffffff812c8de0-ffffffff812c8def: bpf_lsm_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_lsm_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff8132f6f0)
Location: include/linux/lsm_hook_defs.h:330
Inline: False
```
**Symbols:**

```
ffffffff8132f6f0-ffffffff8132f6ff: bpf_lsm_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_lsm_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81360360)
Location: include/linux/lsm_hook_defs.h:331
Inline: False
```
**Symbols:**

```
ffffffff81360360-ffffffff8136036f: bpf_lsm_req_classify_flow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_lsm_req_classify_flow(const struct request_sock *req, struct flowi_common *flic);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lsm.c (ffffffff81389210)
Location: include/linux/lsm_hook_defs.h:341
Inline: False
```
**Symbols:**

```
ffffffff81389210-ffffffff8138921f: bpf_lsm_req_classify_flow (STB_GLOBAL)
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
