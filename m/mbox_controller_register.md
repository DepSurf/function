# Function: <code>mbox_controller_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff816eb620)
Location: drivers/mailbox/mailbox.c:441
Inline: False
Direct callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff816eb620-ffffffff816eb73a: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81750100)
Location: drivers/mailbox/mailbox.c:441
Inline: False
Direct callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81750100-ffffffff81750219: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8177bcc0)
Location: drivers/mailbox/mailbox.c:440
Inline: False
Direct callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff8177bcc0-ffffffff8177bdd9: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8179a5b0)
Location: drivers/mailbox/mailbox.c:447
Inline: False
Direct callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff8179a5b0-ffffffff8179a6e6: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81810970)
Location: drivers/mailbox/mailbox.c:447
Inline: False
Direct callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81810970-ffffffff81810aa6: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff8185a810)
Location: drivers/mailbox/mailbox.c:447
Inline: False
Direct callers:
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff8185a810-ffffffff8185a946: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffff81879b30)
Location: drivers/mailbox/mailbox.c:477
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81879b30-ffffffff81879c66: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:476
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff818bf859-ffffffff818bf86f: mbox_controller_register.cold (STB_LOCAL)
ffffffff818bf0c0-ffffffff818bf1f5: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:476
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff818f23a9-ffffffff818f23bf: mbox_controller_register.cold (STB_LOCAL)
ffffffff818f1c40-ffffffff818f1d75: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:476
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff819c7c2b-ffffffff819c7c41: mbox_controller_register.cold (STB_LOCAL)
ffffffff819c7770-ffffffff819c78a8: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:478
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81c2d964-ffffffff81c2d97a: mbox_controller_register.cold (STB_LOCAL)
ffffffff819c76c0-ffffffff819c77f8: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:478
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81c1fbca-ffffffff81c1fbe0: mbox_controller_register.cold (STB_LOCAL)
ffffffff819ac600-ffffffff819ac738: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:478
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81d314d7-ffffffff81d3151a: mbox_controller_register.cold (STB_LOCAL)
ffffffff81a5ab10-ffffffff81a5ac67: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:484
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81efd931-ffffffff81efd974: mbox_controller_register.cold (STB_LOCAL)
ffffffff81bca2e0-ffffffff81bca432: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:484
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff820aa1e4-ffffffff820aa20e: mbox_controller_register.cold (STB_LOCAL)
ffffffff81d738c0-ffffffff81d73a3a: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:524
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff8212b6e3-ffffffff8212b70d: mbox_controller_register.cold (STB_LOCAL)
ffffffff81de1690-ffffffff81de1805: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:525
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff8220d2f5-ffffffff8220d31f: mbox_controller_register.cold (STB_LOCAL)
ffffffff81e97650-ffffffff81e977c5: mbox_controller_register (STB_GLOBAL)
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
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffff800010b79d10)
Location: drivers/mailbox/mailbox.c:476
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffff800010b79d10-ffff800010b79e40: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (c0c5f700)
Location: drivers/mailbox/mailbox.c:476
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
**Symbols:**

```
c0c5f700-c0c5f844: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (c000000000c58cd0)
Location: drivers/mailbox/mailbox.c:476
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
**Symbols:**

```
c000000000c58cd0-c000000000c58e70: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mailbox/mailbox.c (ffffffe00072bbc8)
Location: drivers/mailbox/mailbox.c:476
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
```
**Symbols:**

```
ffffffe00072bbc8-ffffffe00072bcb8: mbox_controller_register (STB_GLOBAL)
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
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:476
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff818936d9-ffffffff818936ef: mbox_controller_register.cold (STB_LOCAL)
ffffffff81892f70-ffffffff818930a5: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:476
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff8184bbd9-ffffffff8184bbef: mbox_controller_register.cold (STB_LOCAL)
ffffffff8184b470-ffffffff8184b5a5: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:476
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff818e71d9-ffffffff818e71ef: mbox_controller_register.cold (STB_LOCAL)
ffffffff818e6a70-ffffffff818e6ba5: mbox_controller_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mbox_controller_register(struct mbox_controller *mbox);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mailbox/mailbox.c (0)
Location: drivers/mailbox/mailbox.c:476
Inline: False
Direct callers:
  - drivers/mailbox/mailbox.c:devm_mbox_controller_register
  - drivers/mailbox/pcc.c:pcc_mbox_probe
```
**Symbols:**

```
ffffffff81903e59-ffffffff81903e6f: mbox_controller_register.cold (STB_LOCAL)
ffffffff819036f0-ffffffff81903825: mbox_controller_register (STB_GLOBAL)
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
