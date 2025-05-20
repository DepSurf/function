# Function: <code>mmc_cmdq_switch</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_cmdq_switch(struct mmc_card *card, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8177a910)
Location: drivers/mmc/core/mmc_ops.c:1034
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff8177a910-ffffffff8177a96c: mmc_cmdq_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_cmdq_switch(struct mmc_card *card, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff817f0d60)
Location: drivers/mmc/core/mmc_ops.c:1033
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff817f0d60-ffffffff817f0dbc: mmc_cmdq_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_cmdq_switch(struct mmc_card *card, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8183a050)
Location: drivers/mmc/core/mmc_ops.c:1029
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff8183a050-ffffffff8183a0ac: mmc_cmdq_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_cmdq_switch(struct mmc_card *card, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818660a0)
Location: drivers/mmc/core/mmc_ops.c:972
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff818660a0-ffffffff818660fc: mmc_cmdq_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mmc_cmdq_switch(struct mmc_card *card, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818a9ee0)
Location: drivers/mmc/core/mmc_ops.c:974
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff818a9ee0-ffffffff818a9f3c: mmc_cmdq_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mmc_cmdq_switch(struct mmc_card *card, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818dc330)
Location: drivers/mmc/core/mmc_ops.c:976
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff818dc330-ffffffff818dc38c: mmc_cmdq_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819aef65)
Location: drivers/mmc/core/mmc_ops.c:1006
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff819b15c5)
Location: drivers/mmc/core/mmc_ops.c:1006
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81995e95)
Location: drivers/mmc/core/mmc_ops.c:984
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81a41d65)
Location: drivers/mmc/core/mmc_ops.c:977
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff81baf3f5)
Location: drivers/mmc/core/mmc_ops.c:1007
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
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
In drivers/mmc/core/mmc_ops.c (ffffffff81d52e55)
Location: drivers/mmc/core/mmc_ops.c:1007
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
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
In drivers/mmc/core/mmc_ops.c (ffffffff81dbd825)
Location: drivers/mmc/core/mmc_ops.c:1008
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
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
In drivers/mmc/core/mmc_ops.c (ffffffff81e75e55)
Location: drivers/mmc/core/mmc_ops.c:1008
Inline: True
Inline callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
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
int mmc_cmdq_switch(struct mmc_card *card, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffff800010b36478)
Location: drivers/mmc/core/mmc_ops.c:976
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffff800010b36478-ffff800010b364e8: mmc_cmdq_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_cmdq_switch(struct mmc_card *card, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c0c10f28)
Location: drivers/mmc/core/mmc_ops.c:976
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
c0c10f28-c0c10f98: mmc_cmdq_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_cmdq_switch(struct mmc_card *card, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (c000000000c31680)
Location: drivers/mmc/core/mmc_ops.c:976
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
c000000000c31680-c000000000c31718: mmc_cmdq_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_cmdq_switch(struct mmc_card *card, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffe00070e614)
Location: drivers/mmc/core/mmc_ops.c:976
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffe00070e614-ffffffe00070e668: mmc_cmdq_switch (STB_LOCAL)
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
int mmc_cmdq_switch(struct mmc_card *card, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff8187fcf0)
Location: drivers/mmc/core/mmc_ops.c:976
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff8187fcf0-ffffffff8187fd4c: mmc_cmdq_switch (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mmc_cmdq_switch(struct mmc_card *card, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818d1190)
Location: drivers/mmc/core/mmc_ops.c:976
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff818d1190-ffffffff818d11ec: mmc_cmdq_switch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mmc_cmdq_switch(struct mmc_card *card, bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc_ops.c (ffffffff818edcb0)
Location: drivers/mmc/core/mmc_ops.c:976
Inline: False
Direct callers:
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_disable
  - drivers/mmc/core/mmc_ops.c:mmc_cmdq_enable
```
**Symbols:**

```
ffffffff818edcb0-ffffffff818edd0c: mmc_cmdq_switch (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
