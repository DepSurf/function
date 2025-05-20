# Function: <code>compact_zone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compact_zone(struct zone *zone, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811b74f0)
Location: mm/compaction.c:1339
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone_order
  - mm/compaction.c:__compact_pgdat
```
**Symbols:**

```
ffffffff811b74f0-ffffffff811b7d05: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum compact_result compact_zone(struct zone *zone, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811d0f60)
Location: mm/compaction.c:1469
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:__compact_pgdat
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff811d0f60-ffffffff811d182c: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum compact_result compact_zone(struct zone *zone, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811e0fb0)
Location: mm/compaction.c:1478
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff811e0fb0-ffffffff811e183a: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum compact_result compact_zone(struct zone *zone, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811eaca0)
Location: mm/compaction.c:1512
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff811eaca0-ffffffff811eb5b7: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum compact_result compact_zone(struct zone *zone, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81201020)
Location: mm/compaction.c:1536
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff81201020-ffffffff81201935: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
enum compact_result compact_zone(struct zone *zone, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81222430)
Location: mm/compaction.c:1536
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff81222430-ffffffff81222d31: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
enum compact_result compact_zone(struct zone *zone, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81235480)
Location: mm/compaction.c:1537
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff81235480-ffffffff81235d81: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81246500)
Location: mm/compaction.c:2072
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff81246500-ffffffff81247212: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812549e0)
Location: mm/compaction.c:2072
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff812549e0-ffffffff812556fc: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81283970)
Location: mm/compaction.c:2083
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff81283970-ffffffff81283eba: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128d9f0)
Location: mm/compaction.c:2238
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:proactive_compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff8128d9f0-ffffffff8128df1e: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81293020)
Location: mm/compaction.c:2277
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:proactive_compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff81293020-ffffffff8129355d: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2269
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:proactive_compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff812d3430-ffffffff812d39b1: compact_zone (STB_LOCAL)
ffffffff81cbbb67-ffffffff81cbbbf4: compact_zone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2291
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:proactive_compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff81332240-ffffffff8133284f: compact_zone (STB_LOCAL)
ffffffff81e6d732-ffffffff81e6d7bf: compact_zone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2290
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:proactive_compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff813a8f20-ffffffff813a9530: compact_zone (STB_LOCAL)
ffffffff82063a78-ffffffff82063b05: compact_zone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2353
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:proactive_compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff813dc0c0-ffffffff813dc6fe: compact_zone (STB_LOCAL)
ffffffff820e31a7-ffffffff820e3211: compact_zone.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2428
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:proactive_compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff81405ff0-ffffffff81406648: compact_zone (STB_LOCAL)
ffffffff821bfbb1-ffffffff821bfc0e: compact_zone.cold (STB_LOCAL)
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
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102ebed0)
Location: mm/compaction.c:2072
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffff8000102ebed0-ffff8000102ecbb8: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050ff00)
Location: mm/compaction.c:2072
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:sysctl_compaction_handler
  - mm/compaction.c:try_to_compact_pages
```
**Symbols:**

```
c050ff00-c0510d14: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003af6a0)
Location: mm/compaction.c:2072
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
c0000000003af6a0-c0000000003b06a0: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe0002008e4)
Location: mm/compaction.c:2072
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffe0002008e4-ffffffe0002013d2: compact_zone (STB_LOCAL)
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
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124d030)
Location: mm/compaction.c:2072
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff8124d030-ffffffff8124dd4c: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8123ffd0)
Location: mm/compaction.c:2072
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff8123ffd0-ffffffff81240cec: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124add0)
Location: mm/compaction.c:2072
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff8124add0-ffffffff8124baec: compact_zone (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
enum compact_result compact_zone(struct compact_control *cc, struct capture_control *capc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8125a660)
Location: mm/compaction.c:2072
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_do_work
  - mm/compaction.c:compact_node
  - mm/compaction.c:compact_zone_order
```
**Symbols:**

```
ffffffff8125a660-ffffffff8125b3fd: compact_zone (STB_LOCAL)
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
<b>Return type changed. </b>
<code>int</code> ➡️ <code>enum compact_result</code>
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct capture_control *capc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct zone *zone</code>
</li>
<li>
<b>Param reordered. </b>
<code>zone, cc</code> ➡️ <code>cc, capc</code>
</li>
</ul>
</details>
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
