# Function: <code>tpm_bios_log_teardown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct dentry **lst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_eventlog.c (ffffffff81528140)
Location: drivers/char/tpm/tpm_eventlog.c:448
Inline: False
```
**Symbols:**

```
ffffffff81528140-ffffffff8152816a: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct dentry **lst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_eventlog.c (ffffffff8157b190)
Location: drivers/char/tpm/tpm_eventlog.c:448
Inline: False
```
**Symbols:**

```
ffffffff8157b190-ffffffff8157b1ba: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm_eventlog.c (ffffffff815a6cc0)
Location: drivers/char/tpm/tpm_eventlog.c:442
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff815a6cc0-ffffffff815a6d26: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1_eventlog.c (ffffffff815bba80)
Location: drivers/char/tpm/tpm1_eventlog.c:449
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff815bba80-ffffffff815bbae6: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm1_eventlog.c (ffffffff81621fd0)
Location: drivers/char/tpm/tpm1_eventlog.c:449
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/tpm1_eventlog.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81621fd0-ffffffff81622036: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff8165b9a0)
Location: drivers/char/tpm/eventlog/common.c:175
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8165b9a0-ffffffff8165ba06: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff8167a9f0)
Location: drivers/char/tpm/eventlog/common.c:175
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff8167a9f0-ffffffff8167aa56: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff816b13c0)
Location: drivers/char/tpm/eventlog/common.c:170
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816b13c0-ffffffff816b1426: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff816d40a0)
Location: drivers/char/tpm/eventlog/common.c:170
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816d40a0-ffffffff816d4106: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff8178843c)
Location: drivers/char/tpm/eventlog/common.c:166
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
```
**Symbols:**

```
ffffffff817884d0-ffffffff81788536: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff8179f35c)
Location: drivers/char/tpm/eventlog/common.c:166
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
```
**Symbols:**

```
ffffffff8179f3f0-ffffffff8179f456: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff81781ffa)
Location: drivers/char/tpm/eventlog/common.c:169
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
```
**Symbols:**

```
ffffffff817820a0-ffffffff81782106: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff81808888)
Location: drivers/char/tpm/eventlog/common.c:169
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
```
**Symbols:**

```
ffffffff818089a0-ffffffff81808a53: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff819487de)
Location: drivers/char/tpm/eventlog/common.c:169
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
```
**Symbols:**

```
ffffffff819488f0-ffffffff819489ae: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff81aabc6e)
Location: drivers/char/tpm/eventlog/common.c:169
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
```
**Symbols:**

```
ffffffff81aabd90-ffffffff81aabe4e: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff81af74ce)
Location: drivers/char/tpm/eventlog/common.c:169
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
```
**Symbols:**

```
ffffffff81af75f0-ffffffff81af76ae: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff81b4aabe)
Location: drivers/char/tpm/eventlog/common.c:169
Inline: True
Inline callers:
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
```
**Symbols:**

```
ffffffff81b4abe0-ffffffff81b4ac9e: tpm_bios_log_teardown (STB_GLOBAL)
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
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffff8000108beca0)
Location: drivers/char/tpm/eventlog/common.c:170
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffff8000108beca0-ffff8000108bed0c: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (c09b8090)
Location: drivers/char/tpm/eventlog/common.c:170
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
c09b8090-c09b80f4: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (c000000000961270)
Location: drivers/char/tpm/eventlog/common.c:170
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
c000000000961270-c00000000096130c: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffe0005712e8)
Location: drivers/char/tpm/eventlog/common.c:170
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffe0005712e8-ffffffe000571350: tpm_bios_log_teardown (STB_GLOBAL)
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
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff81699af0)
Location: drivers/char/tpm/eventlog/common.c:170
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff81699af0-ffffffff81699b56: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff816774e0)
Location: drivers/char/tpm/eventlog/common.c:170
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816774e0-ffffffff81677546: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff816c7d60)
Location: drivers/char/tpm/eventlog/common.c:170
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816c7d60-ffffffff816c7dc6: tpm_bios_log_teardown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tpm_bios_log_teardown(struct tpm_chip *chip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/eventlog/common.c (ffffffff816e2240)
Location: drivers/char/tpm/eventlog/common.c:170
Inline: False
Direct callers:
  - drivers/char/tpm/tpm-chip.c:tpm_chip_unregister
  - drivers/char/tpm/eventlog/common.c:tpm_bios_log_setup
```
**Symbols:**

```
ffffffff816e2240-ffffffff816e22a6: tpm_bios_log_teardown (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct tpm_chip *chip</code>
</li>
<li>
<b>Param removed. </b>
<code>struct dentry **lst</code>
</li>
</ul>
</details>
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
