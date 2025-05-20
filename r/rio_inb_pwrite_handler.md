# Function: <code>rio_inb_pwrite_handler</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int rio_inb_pwrite_handler(union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8145a620)
Location: drivers/rapidio/rio.c:873
Inline: False
```
**Symbols:**

```
ffffffff8145a620-ffffffff8145abcb: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814a8630)
Location: drivers/rapidio/rio.c:1182
Inline: False
```
**Symbols:**

```
ffffffff814a8630-ffffffff814a8cb9: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814ca740)
Location: drivers/rapidio/rio.c:1182
Inline: False
```
**Symbols:**

```
ffffffff814ca740-ffffffff814cadc9: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814d6560)
Location: drivers/rapidio/rio.c:1179
Inline: False
```
**Symbols:**

```
ffffffff814d6560-ffffffff814d6bc0: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81516a40)
Location: drivers/rapidio/rio.c:1179
Inline: False
```
**Symbols:**

```
ffffffff81516a40-ffffffff815170ab: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1174
Inline: False
```
**Symbols:**

```
ffffffff8154ceac-ffffffff8154cef1: rio_inb_pwrite_handler.cold.20 (STB_LOCAL)
ffffffff8154bc70-ffffffff8154c2a6: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1174
Inline: False
```
**Symbols:**

```
ffffffff815642ec-ffffffff81564331: rio_inb_pwrite_handler.cold.21 (STB_LOCAL)
ffffffff81563000-ffffffff81563636: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff81594672-ffffffff815946b1: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff815933c0-ffffffff815939dd: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff815b5902-ffffffff815b5941: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff815b4640-ffffffff815b4c5d: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff8165f5bc-ffffffff8165f60d: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff8165ee10-ffffffff8165f3b2: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff81bfe432-ffffffff81bfe483: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff816801c0-ffffffff8168075f: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff81befff6-ffffffff81bf0037: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff81662560-ffffffff81662c52: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff81ceb660-ffffffff81ceb735: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff816d5390-ffffffff816d5a91: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff81eb2a75-ffffffff81eb2b75: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff817ff5a0-ffffffff817ffc33: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff82090230-ffffffff820902c0: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff8192c8d0-ffffffff8192cfc3: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff821105ce-ffffffff82110620: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff81970b60-ffffffff8197125f: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff821ee3cb-ffffffff821ee41d: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff819babd0-ffffffff819bb2cf: rio_inb_pwrite_handler (STB_GLOBAL)
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
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffff80001073c6e0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffff80001073c6e0-ffff80001073ccd0: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (c08c2534)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
c08c2534-c08c2bc8: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (c000000000896240)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
c000000000896240-c0000000008969c8: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffe0004ec558)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffe0004ec558-ffffffe0004ecae2: rio_inb_pwrite_handler (STB_GLOBAL)
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
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff815a9b72-ffffffff815a9bb1: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff815a88b0-ffffffff815a8ecd: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff81598d12-ffffffff81598d51: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff81597a50-ffffffff8159806d: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff815aa102-ffffffff815aa141: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff815a8e40-ffffffff815a945d: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int rio_inb_pwrite_handler(struct rio_mport *mport, union rio_pw_msg *pw_msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rapidio/rio.c (0)
Location: drivers/rapidio/rio.c:1170
Inline: False
```
**Symbols:**

```
ffffffff815c3ac2-ffffffff815c3b01: rio_inb_pwrite_handler.cold (STB_LOCAL)
ffffffff815c32c0-ffffffff815c38dd: rio_inb_pwrite_handler (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rio_mport *mport</code>
</li>
<li>
<b>Param reordered. </b>
<code>pw_msg</code> ➡️ <code>mport, pw_msg</code>
</li>
</ul>
</details>
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
