# Function: <code>open_wait</code>

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
In drivers/scsi/sg.c (ffffffff815c505e)
Location: drivers/scsi/sg.c:236
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8161d841)
Location: drivers/scsi/sg.c:236
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8164e442)
Location: drivers/scsi/sg.c:225
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81662b0b)
Location: drivers/scsi/sg.c:224
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff816cc37c)
Location: drivers/scsi/sg.c:224
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81708a8e)
Location: drivers/scsi/sg.c:251
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8172af7e)
Location: drivers/scsi/sg.c:251
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8176668d)
Location: drivers/scsi/sg.c:246
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8178a67d)
Location: drivers/scsi/sg.c:246
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int open_wait(Sg_device *sdp, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8184caf0)
Location: drivers/scsi/sg.c:246
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff8184caf0-ffffffff8184cc90: open_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int open_wait(Sg_device *sdp, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8185cf10)
Location: drivers/scsi/sg.c:246
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff8185cf10-ffffffff8185d0b0: open_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int open_wait(Sg_device *sdp, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8183fe00)
Location: drivers/scsi/sg.c:246
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff8183fe00-ffffffff8183ffa0: open_wait (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int open_wait(Sg_device *sdp, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:247
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff818cce40-ffffffff818cd017: open_wait (STB_LOCAL)
ffffffff81d0d2df-ffffffff81d0d326: open_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int open_wait(Sg_device *sdp, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:246
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81a1a980-ffffffff81a1abb4: open_wait (STB_LOCAL)
ffffffff81ed6240-ffffffff81ed6287: open_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int open_wait(Sg_device *sdp, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:246
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81b9bb60-ffffffff81b9bd94: open_wait (STB_LOCAL)
ffffffff8209c3ad-ffffffff8209c3f4: open_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int open_wait(Sg_device *sdp, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:246
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81bf2150-ffffffff81bf2384: open_wait (STB_LOCAL)
ffffffff8211d2e6-ffffffff8211d32d: open_wait.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int open_wait(Sg_device *sdp, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/sg.c (0)
Location: drivers/scsi/sg.c:246
Inline: False
Direct callers:
  - drivers/scsi/sg.c:sg_open
```
**Symbols:**

```
ffffffff81c47a40-ffffffff81c47c74: open_wait (STB_LOCAL)
ffffffff821fb31e-ffffffff821fb365: open_wait.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffff8000109921c8)
Location: drivers/scsi/sg.c:246
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (c0a636d4)
Location: drivers/scsi/sg.c:246
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (c000000000a54328)
Location: drivers/scsi/sg.c:246
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffe0005f505e)
Location: drivers/scsi/sg.c:246
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8173ed6d)
Location: drivers/scsi/sg.c:246
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff81720a0d)
Location: drivers/scsi/sg.c:246
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff8177f4fd)
Location: drivers/scsi/sg.c:246
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/sg.c (ffffffff817992fd)
Location: drivers/scsi/sg.c:246
Inline: True
Inline callers:
  - drivers/scsi/sg.c:sg_open
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
