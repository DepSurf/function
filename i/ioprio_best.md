# Function: <code>ioprio_best</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff813cdf10)
Location: block/ioprio.c:159
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_get
Direct callers:
  - block/blk-merge.c:attempt_merge
```
**Symbols:**

```
ffffffff813cdf10-ffffffff813cdf6f: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814124ee)
Location: block/ioprio.c:161
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_get
```
**Symbols:**

```
ffffffff81412370-ffffffff814123cf: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8142d94e)
Location: block/ioprio.c:161
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_get
```
**Symbols:**

```
ffffffff8142d7d0-ffffffff8142d82f: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8143ac95)
Location: block/ioprio.c:165
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_get
Direct callers:
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-merge.c:attempt_merge
```
**Symbols:**

```
ffffffff8143aaf0-ffffffff8143ab34: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81466cb5)
Location: block/ioprio.c:165
Inline: True
Inline callers:
  - block/ioprio.c:SyS_ioprio_get
  - block/ioprio.c:SyS_ioprio_get
Direct callers:
  - block/blk-core.c:bio_attempt_discard_merge
  - block/blk-merge.c:attempt_merge
```
**Symbols:**

```
ffffffff81466b10-ffffffff81466b54: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8149a22a)
Location: block/ioprio.c:175
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
Direct callers:
  - block/blk-core.c:bio_attempt_discard_merge
```
**Symbols:**

```
ffffffff8149ad00-ffffffff8149ad2b: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814b453a)
Location: block/ioprio.c:175
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff814b5010-ffffffff814b503b: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814e2a59)
Location: block/ioprio.c:176
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff814e35b0-ffffffff814e35db: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814fbe19)
Location: block/ioprio.c:176
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff814fc970-ffffffff814fc99b: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8155baa2)
Location: block/ioprio.c:176
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
```
**Symbols:**

```
ffffffff8155c0d0-ffffffff8155c0fb: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81577c0a)
Location: block/ioprio.c:176
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
```
**Symbols:**

```
ffffffff81578230-ffffffff8157825b: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff8157f94a)
Location: block/ioprio.c:183
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
```
**Symbols:**

```
ffffffff8157ffb0-ffffffff8157ffdb: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff815e4bfd)
Location: block/ioprio.c:189
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
```
**Symbols:**

```
ffffffff815e5290-ffffffff815e52c9: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81693c16)
Location: block/ioprio.c:157
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
```
**Symbols:**

```
ffffffff81694310-ffffffff81694353: ioprio_best (STB_GLOBAL)
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
In block/ioprio.c (ffffffff81752c32)
Location: block/ioprio.c:204
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
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
In block/ioprio.c (ffffffff8178ef8b)
Location: block/ioprio.c:205
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
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
In block/ioprio.c (ffffffff817d1877)
Location: block/ioprio.c:179
Inline: True
Inline callers:
  - block/ioprio.c:__do_sys_ioprio_get
  - block/ioprio.c:__do_sys_ioprio_get
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffff8000105fdeb0)
Location: block/ioprio.c:176
Inline: True
Inline callers:
  - block/ioprio.c:__arm64_sys_ioprio_get
  - block/ioprio.c:__arm64_sys_ioprio_get
```
**Symbols:**

```
ffff8000105fe398-ffff8000105fe3e0: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (c07a9090)
Location: block/ioprio.c:176
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_get
```
**Symbols:**

```
c07a8fa8-c07a8fdc: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (c000000000797990)
Location: block/ioprio.c:176
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_get
```
**Symbols:**

```
c0000000007980b0-c0000000007980e4: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffe000439ab8)
Location: block/ioprio.c:176
Inline: True
Inline callers:
  - block/ioprio.c:__se_sys_ioprio_get
  - block/ioprio.c:__se_sys_ioprio_get
```
**Symbols:**

```
ffffffe0004399f6-ffffffe000439a3c: ioprio_best (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814f43f9)
Location: block/ioprio.c:176
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff814f4f50-ffffffff814f4f7b: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814e4909)
Location: block/ioprio.c:176
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff814e5460-ffffffff814e548b: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff814f0489)
Location: block/ioprio.c:176
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff814f0fe0-ffffffff814f100b: ioprio_best (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ioprio_best(short unsigned int aprio, short unsigned int bprio);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/ioprio.c (ffffffff81509536)
Location: block/ioprio.c:176
Inline: True
Inline callers:
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__ia32_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
  - block/ioprio.c:__x64_sys_ioprio_get
```
**Symbols:**

```
ffffffff8150a040-ffffffff8150a06b: ioprio_best (STB_GLOBAL)
```
</details>
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
