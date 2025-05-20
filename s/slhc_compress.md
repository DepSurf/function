# Function: <code>slhc_compress</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/slip/slhc.c (ffffffff815f8f90)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
**Symbols:**

```
ffffffff815f8f90-ffffffff815f9706: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/slip/slhc.c (ffffffff81658ee0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_xmit_process
```
**Symbols:**

```
ffffffff81658ee0-ffffffff816595fd: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/slip/slhc.c (ffffffff81686c70)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff81686c70-ffffffff81687383: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/slip/slhc.c (ffffffff8169c010)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff8169c010-ffffffff8169c736: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/slip/slhc.c (ffffffff81707060)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff81707060-ffffffff8170778c: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/slip/slhc.c (0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff81746d0f-ffffffff81746d1b: slhc_compress.cold.4 (STB_LOCAL)
ffffffff81745d60-ffffffff81746452: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/slip/slhc.c (0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:__ppp_xmit_process
```
**Symbols:**

```
ffffffff8176ae1f-ffffffff8176ae2b: slhc_compress.cold.4 (STB_LOCAL)
ffffffff81769e50-ffffffff8176a56b: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/slip/slhc.c (0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff817a8c09-ffffffff817a8c15: slhc_compress.cold (STB_LOCAL)
ffffffff817a7bb0-ffffffff817a82e3: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/slip/slhc.c (0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff817cc679-ffffffff817cc685: slhc_compress.cold (STB_LOCAL)
ffffffff817cb620-ffffffff817cbd59: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/slip/slhc.c (0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81896ca0-ffffffff81896cac: slhc_compress.cold (STB_LOCAL)
ffffffff81895bd0-ffffffff8189634a: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/slip/slhc.c (0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81c19c65-ffffffff81c19c71: slhc_compress.cold (STB_LOCAL)
ffffffff818a3fa0-ffffffff818a471a: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/slip/slhc.c (0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81c0babc-ffffffff81c0bac8: slhc_compress.cold (STB_LOCAL)
ffffffff81886a00-ffffffff8188717c: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/slip/slhc.c (0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81d11132-ffffffff81d1113e: slhc_compress.cold (STB_LOCAL)
ffffffff819183f0-ffffffff81918b6c: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/slip/slhc.c (0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81edbe1c-ffffffff81edbe28: slhc_compress.cold (STB_LOCAL)
ffffffff81a6d360-ffffffff81a6dbac: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/slip/slhc.c (ffffffff81c00320)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81c00320-ffffffff81c00b7b: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/slip/slhc.c (ffffffff81c65950)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81c65950-ffffffff81c66157: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/slip/slhc.c (ffffffff81d1c380)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81d1c380-ffffffff81d1cb87: slhc_compress (STB_GLOBAL)
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
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/slip/slhc.c (ffff800010a05180)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffff800010a05180-ffff800010a05860: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/slip/slhc.c (c0ae06b8)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
c0ae06b8-c0ae0dd0: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/slip/slhc.c (c000000000aac410)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
c000000000aac410-c000000000aacc8c: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/slip/slhc.c (ffffffe00062f972)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffe00062f972-ffffffe00062ffee: slhc_compress (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/slip/slhc.c (0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81791159-ffffffff81791165: slhc_compress.cold (STB_LOCAL)
ffffffff81790100-ffffffff81790839: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/slip/slhc.c (0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff81779f29-ffffffff81779f35: slhc_compress.cold (STB_LOCAL)
ffffffff81778ed0-ffffffff81779609: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/slip/slhc.c (0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff817c14f9-ffffffff817c1505: slhc_compress.cold (STB_LOCAL)
ffffffff817c04a0-ffffffff817c0bd9: slhc_compress (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int slhc_compress(struct slcompress *comp, unsigned char *icp, int isize, unsigned char *ocp, unsigned char **cpp, int compress_cid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/slip/slhc.c (0)
Location: drivers/net/slip/slhc.c:227
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_send_frame
```
**Symbols:**

```
ffffffff817db7b9-ffffffff817db7c5: slhc_compress.cold (STB_LOCAL)
ffffffff817da760-ffffffff817dae99: slhc_compress (STB_GLOBAL)
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
