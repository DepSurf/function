# Function: <code>scsi_kick_queue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void scsi_kick_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff815ad370)
Location: drivers/scsi/scsi_lib.c:329
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff815ad370-ffffffff815ad391: scsi_kick_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void scsi_kick_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816052a0)
Location: drivers/scsi/scsi_lib.c:295
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff816052a0-ffffffff816052c1: scsi_kick_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void scsi_kick_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816347c0)
Location: drivers/scsi/scsi_lib.c:304
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff816347c0-ffffffff816347e1: scsi_kick_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_kick_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81649810)
Location: drivers/scsi/scsi_lib.c:333
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff81649810-ffffffff81649831: scsi_kick_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void scsi_kick_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b2a30)
Location: drivers/scsi/scsi_lib.c:358
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff816b2a30-ffffffff816b2a51: scsi_kick_queue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void scsi_kick_queue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816eeba0)
Location: drivers/scsi/scsi_lib.c:371
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff816eeba0-ffffffff816eebc1: scsi_kick_queue (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffffffff81712887)
Location: drivers/scsi/scsi_lib.c:363
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff8174e1f3)
Location: drivers/scsi/scsi_lib.c:360
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff817723a3)
Location: drivers/scsi/scsi_lib.c:360
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff818349cf)
Location: drivers/scsi/scsi_lib.c:349
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
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
In drivers/scsi/scsi_lib.c (ffffffff818453af)
Location: drivers/scsi/scsi_lib.c:334
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
  - drivers/scsi/scsi_lib.c:scsi_single_lun_run
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
In drivers/scsi/scsi_lib.c (ffffffff818284fb)
Location: drivers/scsi/scsi_lib.c:301
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
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
In drivers/scsi/scsi_lib.c (ffffffff818b3e3b)
Location: drivers/scsi/scsi_lib.c:306
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
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
In drivers/scsi/scsi_lib.c (ffffffff819fee2a)
Location: drivers/scsi/scsi_lib.c:307
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
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
In drivers/scsi/scsi_lib.c (ffffffff81b7d473)
Location: drivers/scsi/scsi_lib.c:305
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
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
In drivers/scsi/scsi_lib.c (ffffffff81bd11fe)
Location: drivers/scsi/scsi_lib.c:303
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_starved_list_run
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In drivers/scsi/scsi_lib.c (ffff80001097750c)
Location: drivers/scsi/scsi_lib.c:360
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (c0a4a134)
Location: drivers/scsi/scsi_lib.c:360
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (c000000000a2fa80)
Location: drivers/scsi/scsi_lib.c:360
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffe0005de078)
Location: drivers/scsi/scsi_lib.c:360
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff81726a93)
Location: drivers/scsi/scsi_lib.c:360
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff816ffec3)
Location: drivers/scsi/scsi_lib.c:360
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff81765863)
Location: drivers/scsi/scsi_lib.c:360
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff81780ef3)
Location: drivers/scsi/scsi_lib.c:360
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
</ul>
