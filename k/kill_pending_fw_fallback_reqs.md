# Function: <code>kill_pending_fw_fallback_reqs</code>

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
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f72d0)
Location: drivers/base/firmware_class.c:599
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff815f72d0-ffffffff815f7343: kill_pending_fw_fallback_reqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8165f210)
Location: drivers/base/firmware_class.c:603
Inline: False
Direct callers:
  - drivers/base/firmware_class.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff8165f210-ffffffff8165f283: kill_pending_fw_fallback_reqs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8169b930)
Location: drivers/base/firmware_loader/fallback.c:107
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff8169b930-ffffffff8169b9a3: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816bc1b0)
Location: drivers/base/firmware_loader/fallback.c:107
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff816bc1b0-ffffffff816bc223: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816f6810)
Location: drivers/base/firmware_loader/fallback.c:107
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff816f6810-ffffffff816f688f: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8171ac10)
Location: drivers/base/firmware_loader/fallback.c:107
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff8171ac10-ffffffff8171ac8f: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff817d6f00)
Location: drivers/base/firmware_loader/fallback.c:110
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff817d6f00-ffffffff817d6fa8: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff817eb920)
Location: drivers/base/firmware_loader/fallback.c:110
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff817eb920-ffffffff817eb9d3: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff817d0100)
Location: drivers/base/firmware_loader/fallback.c:109
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff817d0100-ffffffff817d01b8: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:109
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff81d043b8-ffffffff81d043cd: kill_pending_fw_fallback_reqs.cold (STB_LOCAL)
ffffffff8185a910-ffffffff8185a9ee: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:49
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff81eccc94-ffffffff81eccca9: kill_pending_fw_fallback_reqs.cold (STB_LOCAL)
ffffffff819a0cc0-ffffffff819a0d6e: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:49
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff82098b7c-ffffffff82098b91: kill_pending_fw_fallback_reqs.cold (STB_LOCAL)
ffffffff81b12950-ffffffff81b129fe: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:49
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff82119b33-ffffffff82119b48: kill_pending_fw_fallback_reqs.cold (STB_LOCAL)
ffffffff81b60c40-ffffffff81b60cee: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void kill_pending_fw_fallback_reqs(bool kill_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (0)
Location: drivers/base/firmware_loader/fallback.c:49
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff821f7a20-ffffffff821f7a35: kill_pending_fw_fallback_reqs.cold (STB_LOCAL)
ffffffff81bb4680-ffffffff81bb4779: kill_pending_fw_fallback_reqs (STB_GLOBAL)
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
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffff80001090e4b0)
Location: drivers/base/firmware_loader/fallback.c:107
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffff80001090e4b0-ffff80001090e548: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (c09f7334)
Location: drivers/base/firmware_loader/fallback.c:107
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
c09f7334-c09f73bc: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (c0000000009af330)
Location: drivers/base/firmware_loader/fallback.c:107
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
c0000000009af330-c0000000009af420: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffe000592b3e)
Location: drivers/base/firmware_loader/fallback.c:107
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffe000592b3e-ffffffe000592bd0: kill_pending_fw_fallback_reqs (STB_GLOBAL)
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
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816e0f40)
Location: drivers/base/firmware_loader/fallback.c:107
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff816e0f40-ffffffff816e0fbf: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff816bb580)
Location: drivers/base/firmware_loader/fallback.c:107
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff816bb580-ffffffff816bb5ff: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff8170e610)
Location: drivers/base/firmware_loader/fallback.c:107
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff8170e610-ffffffff8170e68f: kill_pending_fw_fallback_reqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kill_pending_fw_fallback_reqs(bool only_kill_custom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/fallback.c (ffffffff81729230)
Location: drivers/base/firmware_loader/fallback.c:107
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:fw_shutdown_notify
```
**Symbols:**

```
ffffffff81729230-ffffffff817292af: kill_pending_fw_fallback_reqs (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool kill_all</code>
</li>
<li>
<b>Param removed. </b>
<code>bool only_kill_custom</code>
</li>
</ul>
</details>
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
