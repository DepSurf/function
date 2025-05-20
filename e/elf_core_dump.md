# Function: <code>elf_core_dump</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81268d60)
Location: fs/binfmt_elf.c:2124
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff8126baa0)
Location: fs/binfmt_elf.c:2124
Inline: False
```
**Symbols:**

```
ffffffff81268d60-ffffffff81269797: elf_core_dump (STB_LOCAL)
ffffffff8126baa0-ffffffff8126c4f1: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81295000)
Location: fs/binfmt_elf.c:2132
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff81297c70)
Location: fs/binfmt_elf.c:2132
Inline: False
```
**Symbols:**

```
ffffffff81295000-ffffffff81295a98: elf_core_dump (STB_LOCAL)
ffffffff81297c70-ffffffff81298723: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812a9cc0)
Location: fs/binfmt_elf.c:2125
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff812ac760)
Location: fs/binfmt_elf.c:2125
Inline: False
```
**Symbols:**

```
ffffffff812a9cc0-ffffffff812aa6e1: elf_core_dump (STB_LOCAL)
ffffffff812ac760-ffffffff812ad1a1: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812b6640)
Location: fs/binfmt_elf.c:2184
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff812b9750)
Location: fs/binfmt_elf.c:2184
Inline: False
```
**Symbols:**

```
ffffffff812b6640-ffffffff812b703e: elf_core_dump (STB_LOCAL)
ffffffff812b9750-ffffffff812ba114: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff812d9f30)
Location: fs/binfmt_elf.c:2198
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff812dd080)
Location: fs/binfmt_elf.c:2198
Inline: False
```
**Symbols:**

```
ffffffff812d9f30-ffffffff812da92c: elf_core_dump (STB_LOCAL)
ffffffff812dd080-ffffffff812dda43: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81305ba0)
Location: fs/binfmt_elf.c:2212
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff81309550)
Location: fs/binfmt_elf.c:2212
Inline: False
```
**Symbols:**

```
ffffffff81305ba0-ffffffff813066b2: elf_core_dump (STB_LOCAL)
ffffffff81309550-ffffffff8130a057: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8131b330)
Location: fs/binfmt_elf.c:2212
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff8131ed50)
Location: fs/binfmt_elf.c:2212
Inline: False
```
**Symbols:**

```
ffffffff8131b330-ffffffff8131be2e: elf_core_dump (STB_LOCAL)
ffffffff8131ed50-ffffffff8131f82c: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Transformation ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/binfmt_elf.c (0)
Location: fs/binfmt_elf.c:2210
Inline: False
```
```
In fs/compat_binfmt_elf.c (0)
Location: fs/binfmt_elf.c:2210
Inline: False
```
**Symbols:**

```
ffffffff81342c10-ffffffff813436a8: elf_core_dump (STB_LOCAL)
ffffffff813436e7-ffffffff813436fa: elf_core_dump.cold (STB_LOCAL)
ffffffff813465c0-ffffffff81347027: elf_core_dump (STB_LOCAL)
ffffffff81347066-ffffffff81347079: elf_core_dump.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8135b050)
Location: fs/binfmt_elf.c:2184
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff8135e8d0)
Location: fs/binfmt_elf.c:2184
Inline: False
```
**Symbols:**

```
ffffffff8135b050-ffffffff8135bae6: elf_core_dump (STB_LOCAL)
ffffffff8135e8d0-ffffffff8135f335: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8139fed0)
Location: fs/binfmt_elf.c:2304
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff813a3190)
Location: fs/binfmt_elf.c:2304
Inline: False
```
**Symbols:**

```
ffffffff8139fed0-ffffffff813a0607: elf_core_dump (STB_LOCAL)
ffffffff813a3190-ffffffff813a38bd: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b12d0)
Location: fs/binfmt_elf.c:2154
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff813b4150)
Location: fs/binfmt_elf.c:2154
Inline: False
```
**Symbols:**

```
ffffffff813b12d0-ffffffff813b176e: elf_core_dump (STB_LOCAL)
ffffffff813b4150-ffffffff813b45f6: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813b83c0)
Location: fs/binfmt_elf.c:2154
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff813bb120)
Location: fs/binfmt_elf.c:2154
Inline: False
```
**Symbols:**

```
ffffffff813b83c0-ffffffff813b8913: elf_core_dump (STB_LOCAL)
ffffffff813bb120-ffffffff813bb67e: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81407f30)
Location: fs/binfmt_elf.c:2156
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff8140ae20)
Location: fs/binfmt_elf.c:2156
Inline: False
```
**Symbols:**

```
ffffffff81407f30-ffffffff81408483: elf_core_dump (STB_LOCAL)
ffffffff8140ae20-ffffffff8140b37e: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8147cca0)
Location: fs/binfmt_elf.c:2195
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff8147fc00)
Location: fs/binfmt_elf.c:2195
Inline: False
```
**Symbols:**

```
ffffffff8147cca0-ffffffff8147d1a4: elf_core_dump (STB_LOCAL)
ffffffff8147fc00-ffffffff814800f7: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8150f9c0)
Location: fs/binfmt_elf.c:2021
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff81512ce0)
Location: fs/binfmt_elf.c:2021
Inline: False
```
**Symbols:**

```
ffffffff8150f9c0-ffffffff8150fec4: elf_core_dump (STB_LOCAL)
ffffffff81512ce0-ffffffff815131d7: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff815472f0)
Location: fs/binfmt_elf.c:2026
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff8154a720)
Location: fs/binfmt_elf.c:2026
Inline: False
```
**Symbols:**

```
ffffffff815472f0-ffffffff815477ef: elf_core_dump (STB_LOCAL)
ffffffff8154a720-ffffffff8154ac23: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff8157c740)
Location: fs/binfmt_elf.c:1961
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff8157f780)
Location: fs/binfmt_elf.c:1961
Inline: False
```
**Symbols:**

```
ffffffff8157c740-ffffffff8157cc97: elf_core_dump (STB_LOCAL)
ffffffff8157f780-ffffffff8157fcdb: elf_core_dump (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffff800010420a40)
Location: fs/binfmt_elf.c:2184
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffff8000104242e8)
Location: fs/binfmt_elf.c:2184
Inline: False
```
**Symbols:**

```
ffff800010420a40-ffff8000104212e0: elf_core_dump (STB_LOCAL)
ffff8000104242e8-ffff800010424b94: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c05e8964)
Location: fs/binfmt_elf.c:2184
Inline: False
```
**Symbols:**

```
c05e8964-c05e9330: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (c00000000052f600)
Location: fs/binfmt_elf.c:2184
Inline: False
```
```
In fs/compat_binfmt_elf.c (c000000000533220)
Location: fs/binfmt_elf.c:2184
Inline: False
```
**Symbols:**

```
c00000000052f600-c00000000053015c: elf_core_dump (STB_LOCAL)
c000000000533220-c000000000533d6c: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffe0002c14dc)
Location: fs/binfmt_elf.c:2184
Inline: False
```
**Symbols:**

```
ffffffe0002c14dc-ffffffe0002c1ba8: elf_core_dump (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81353630)
Location: fs/binfmt_elf.c:2184
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff81356eb0)
Location: fs/binfmt_elf.c:2184
Inline: False
```
**Symbols:**

```
ffffffff81353630-ffffffff813540c6: elf_core_dump (STB_LOCAL)
ffffffff81356eb0-ffffffff81357915: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813442f0)
Location: fs/binfmt_elf.c:2184
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff81347b60)
Location: fs/binfmt_elf.c:2184
Inline: False
```
**Symbols:**

```
ffffffff813442f0-ffffffff81344d86: elf_core_dump (STB_LOCAL)
ffffffff81347b60-ffffffff813485c5: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff81351100)
Location: fs/binfmt_elf.c:2184
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff81354980)
Location: fs/binfmt_elf.c:2184
Inline: False
```
**Symbols:**

```
ffffffff81351100-ffffffff81351b96: elf_core_dump (STB_LOCAL)
ffffffff81354980-ffffffff813553e5: elf_core_dump (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate ⚠️</summary>

```c
int elf_core_dump(struct coredump_params *cprm);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/binfmt_elf.c (ffffffff813646a0)
Location: fs/binfmt_elf.c:2184
Inline: False
```
```
In fs/compat_binfmt_elf.c (ffffffff81367f60)
Location: fs/binfmt_elf.c:2184
Inline: False
```
**Symbols:**

```
ffffffff813646a0-ffffffff81365131: elf_core_dump (STB_LOCAL)
ffffffff81367f60-ffffffff813689c0: elf_core_dump (STB_LOCAL)
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
