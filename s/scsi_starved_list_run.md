# Function: <code>scsi_starved_list_run</code>

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
In drivers/scsi/scsi_lib.c (ffffffff815ad3f6)
Location: drivers/scsi/scsi_lib.c:415
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff81605329)
Location: drivers/scsi/scsi_lib.c:381
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff81634849)
Location: drivers/scsi/scsi_lib.c:390
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff8164989a)
Location: drivers/scsi/scsi_lib.c:419
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff816b2aba)
Location: drivers/scsi/scsi_lib.c:444
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff816eec2a)
Location: drivers/scsi/scsi_lib.c:457
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
In drivers/scsi/scsi_lib.c (ffffffff81712798)
Location: drivers/scsi/scsi_lib.c:446
Inline: True
Inline callers:
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
In drivers/scsi/scsi_lib.c (ffffffff8174e105)
Location: drivers/scsi/scsi_lib.c:443
Inline: True
Inline callers:
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
In drivers/scsi/scsi_lib.c (ffffffff817722b5)
Location: drivers/scsi/scsi_lib.c:443
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void scsi_starved_list_run(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81834880)
Location: drivers/scsi/scsi_lib.c:429
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff81834880-ffffffff818349f7: scsi_starved_list_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void scsi_starved_list_run(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81845260)
Location: drivers/scsi/scsi_lib.c:414
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff81845260-ffffffff818453d7: scsi_starved_list_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void scsi_starved_list_run(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81828300)
Location: drivers/scsi/scsi_lib.c:381
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff81828300-ffffffff81828477: scsi_starved_list_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void scsi_starved_list_run(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b3c40)
Location: drivers/scsi/scsi_lib.c:386
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff818b3c40-ffffffff818b3db7: scsi_starved_list_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_starved_list_run(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff819fec10)
Location: drivers/scsi/scsi_lib.c:387
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff819fec10-ffffffff819fed99: scsi_starved_list_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_starved_list_run(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7d250)
Location: drivers/scsi/scsi_lib.c:383
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff81b7d250-ffffffff81b7d3d9: scsi_starved_list_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_starved_list_run(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd0fd0)
Location: drivers/scsi/scsi_lib.c:381
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff81bd0fd0-ffffffff81bd1159: scsi_starved_list_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_starved_list_run(struct Scsi_Host *shost);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c25c40)
Location: drivers/scsi/scsi_lib.c:379
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
```
**Symbols:**

```
ffffffff81c25c40-ffffffff81c25dc9: scsi_starved_list_run (STB_LOCAL)
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
In drivers/scsi/scsi_lib.c (ffff8000109773f4)
Location: drivers/scsi/scsi_lib.c:443
Inline: True
Inline callers:
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
In drivers/scsi/scsi_lib.c (c0a4a050)
Location: drivers/scsi/scsi_lib.c:443
Inline: True
Inline callers:
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
In drivers/scsi/scsi_lib.c (c000000000a2f984)
Location: drivers/scsi/scsi_lib.c:443
Inline: True
Inline callers:
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
In drivers/scsi/scsi_lib.c (ffffffe0005ddfc2)
Location: drivers/scsi/scsi_lib.c:443
Inline: True
Inline callers:
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
In drivers/scsi/scsi_lib.c (ffffffff817269a5)
Location: drivers/scsi/scsi_lib.c:443
Inline: True
Inline callers:
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
In drivers/scsi/scsi_lib.c (ffffffff816ffdd5)
Location: drivers/scsi/scsi_lib.c:443
Inline: True
Inline callers:
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
In drivers/scsi/scsi_lib.c (ffffffff81765775)
Location: drivers/scsi/scsi_lib.c:443
Inline: True
Inline callers:
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
In drivers/scsi/scsi_lib.c (ffffffff81780e05)
Location: drivers/scsi/scsi_lib.c:443
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_run_queue
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
