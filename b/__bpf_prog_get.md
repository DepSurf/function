# Function: <code>__bpf_prog_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811729ca)
Location: kernel/bpf/syscall.c:571
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81180c30)
Location: kernel/bpf/syscall.c:688
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_get_type
  - kernel/bpf/syscall.c:bpf_prog_get
```
**Symbols:**

```
ffffffff81180c30-ffffffff81180cb6: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118c970)
Location: kernel/bpf/syscall.c:785
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:bpf_prog_get
```
**Symbols:**

```
ffffffff8118c970-ffffffff8118c9f6: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811918c0)
Location: kernel/bpf/syscall.c:890
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff811918c0-ffffffff8119194a: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119f0f0)
Location: kernel/bpf/syscall.c:1075
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:sockmap_get_from_fd
```
**Symbols:**

```
ffffffff8119f0f0-ffffffff8119f190: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b3c20)
Location: kernel/bpf/syscall.c:1176
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_test_run
  - kernel/bpf/syscall.c:bpf_prog_attach
```
**Symbols:**

```
ffffffff811b3c20-ffffffff811b3ccd: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c2120)
Location: kernel/bpf/syscall.c:1362
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811c2120-ffffffff811c21cd: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d2880)
Location: kernel/bpf/syscall.c:1499
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d2880-ffffffff811d2941: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811decd0)
Location: kernel/bpf/syscall.c:1520
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811decd0-ffffffff811ded91: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc8c0)
Location: kernel/bpf/syscall.c:1898
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_test_run
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811fc8c0-ffffffff811fc95e: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fbc10)
Location: kernel/bpf/syscall.c:1872
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_test_run
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811fbc10-ffffffff811fbcb1: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc930)
Location: kernel/bpf/syscall.c:1880
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811fc930-ffffffff811fc9d1: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:1974
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff8122e2b0-ffffffff8122e383: __bpf_prog_get (STB_LOCAL)
ffffffff81cb79de-ffffffff81cb79fa: __bpf_prog_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:2220
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff81270920-ffffffff81270a2c: __bpf_prog_get (STB_LOCAL)
ffffffff81e68b35-ffffffff81e68b51: __bpf_prog_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:2254
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff812c6450-ffffffff812c655c: __bpf_prog_get (STB_LOCAL)
ffffffff8205f821-ffffffff8205f83d: __bpf_prog_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:2333
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff812ed750-ffffffff812ed85f: __bpf_prog_get (STB_LOCAL)
ffffffff820de75d-ffffffff820de779: __bpf_prog_get.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/syscall.c (0)
Location: kernel/bpf/syscall.c:2373
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:kern_sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:bpf_prog_bind_map
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_update
  - kernel/bpf/syscall.c:link_create
  - kernel/bpf/syscall.c:bpf_prog_detach
  - kernel/bpf/syscall.c:bpf_prog_attach
  - kernel/bpf/syscall.c:bpf_tracing_prog_attach
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff8130c300-ffffffff8130c40f: __bpf_prog_get (STB_LOCAL)
ffffffff821ba63c-ffffffff821ba658: __bpf_prog_get.cold (STB_LOCAL)
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
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff80001025ff70)
Location: kernel/bpf/syscall.c:1520
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffff80001025ff70-ffff800010260068: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0493488)
Location: kernel/bpf/syscall.c:1520
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_raw_tracepoint_open
```
**Symbols:**

```
c0493488-c049355c: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000304f30)
Location: kernel/bpf/syscall.c:1520
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
c000000000304f30-c000000000305098: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019dd74)
Location: kernel/bpf/syscall.c:1520
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffe00019dd74-ffffffe00019de46: __bpf_prog_get (STB_LOCAL)
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
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d72f0)
Location: kernel/bpf/syscall.c:1520
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d72f0-ffffffff811d73b1: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811ca0b0)
Location: kernel/bpf/syscall.c:1520
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811ca0b0-ffffffff811ca171: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d50c0)
Location: kernel/bpf/syscall.c:1520
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811d50c0-ffffffff811d5181: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct bpf_prog *__bpf_prog_get(u32 ufd, enum bpf_prog_type *attach_type, bool attach_drv);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e33f0)
Location: kernel/bpf/syscall.c:1520
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff811e33f0-ffffffff811e34b1: __bpf_prog_get (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum bpf_prog_type *attach_type</code>
</li>
<li>
<b>Param added. </b>
<code>bool attach_drv</code>
</li>
<li>
<b>Param removed. </b>
<code>enum bpf_prog_type *type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
