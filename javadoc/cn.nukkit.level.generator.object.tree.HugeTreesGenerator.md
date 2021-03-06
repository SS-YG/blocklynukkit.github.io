<div class="summary">
<ul class="blockList">
<li class="blockList">  
<li class="blockList"><a name="field.summary">
<!--   -->
</a>
<h3>成员变量一览</h3>
<table class="memberSummary" border="0" cellpadding="3" cellspacing="0" summary="Field Summary table, listing fields, and an explanation">
<caption><span>成员变量</span><span class="tabEnd"> </span></caption>
<tr>
<th>修饰符和类</th>
<th>成员变量描述</th>
</tr>
<tr class="altColor">
<td class="colFirst"><code>protected int</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >baseHeight</a></span></code>
<div class="block">The base height of the tree</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><code>protected int</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >extraRandomHeight</a></span></code> </td>
</tr>
<tr class="altColor">
<td class="colFirst"><code>protected <a  title="class in cn.nukkit.block">Block</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a >leavesMetadata</a></span></code>
<div class="block">Sets the metadata for the leaves used in huge trees</div>
</td>
</tr>
<tr class="rowColor">
<td class="colFirst"><code>protected <a  title="class in cn.nukkit.block">Block</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a >woodMetadata</a></span></code>
<div class="block">Sets the metadata for the wood blocks used</div>
</td>
</tr>
</table>
</li>
</ul>
<!-- ======== CONSTRUCTOR SUMMARY ======== -->
<ul class="blockList">
<li class="blockList"><a name="constructor.summary">
<!--   -->
</a>
<h3>构造函数一览</h3>
<table class="memberSummary" border="0" cellpadding="3" cellspacing="0" summary="Constructor Summary table, listing constructors, and an explanation">
<caption><span>构造函数</span><span class="tabEnd"> </span></caption>
<tr>
<th>构造函数描述</th>
</tr>
<tr class="altColor">
<td class="colOne"><code><span class="memberNameLink"><a >HugeTreesGenerator</a></span>(int baseHeightIn,
                  int extraRandomHeightIn,
                  <a  title="class in cn.nukkit.block">Block</a> woodMetadataIn,
                  <a  title="class in cn.nukkit.block">Block</a> leavesMetadataIn)</code> </td>
</tr>
</table>
</li>
</ul>
<!-- ========== METHOD SUMMARY =========== -->
<ul class="blockList">
<li class="blockList"><a name="method.summary">
<!--   -->
</a>
<h3>成员函数一览</h3>
<table class="memberSummary" border="0" cellpadding="3" cellspacing="0" summary="Method Summary table, listing methods, and an explanation">
<caption><span id="t0" class="activeTableTab"><span>All Methods</span><span class="tabEnd"> </span></span><span id="t2" class="tableTab"><span><a >Instance Methods</a></span><span class="tabEnd"> </span></span><span id="t4" class="tableTab"><span><a >Concrete Methods</a></span><span class="tabEnd"> </span></span></caption>
<tr>
<th>修饰符和类</th>
<th>成员函数描述</th>
</tr>
<tr id="i0" class="altColor">
<td class="colFirst"><code>protected boolean</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >ensureGrowable</a></span>(<a  title="interface in cn.nukkit.level">ChunkManager</a> worldIn,
              <a  title="class in cn.nukkit.math">NukkitRandom</a> rand,
              <a  title="class in cn.nukkit.math">Vector3</a> treePos,
              int p_175929_4_)</code> </td>
</tr>
<tr id="i1" class="rowColor">
<td class="colFirst"><code>protected int</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getHeight</a></span>(<a  title="class in cn.nukkit.math">NukkitRandom</a> rand)</code> </td>
</tr>
<tr id="i2" class="altColor">
<td class="colFirst"><code>protected void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >growLeavesLayer</a></span>(<a  title="interface in cn.nukkit.level">ChunkManager</a> worldIn,
               <a  title="class in cn.nukkit.math">Vector3</a> layerCenter,
               int width)</code> </td>
</tr>
<tr id="i3" class="rowColor">
<td class="colFirst"><code>protected void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >growLeavesLayerStrict</a></span>(<a  title="interface in cn.nukkit.level">ChunkManager</a> worldIn,
                     <a  title="class in cn.nukkit.math">Vector3</a> layerCenter,
                     int width)</code> </td>
</tr>
</table>
<ul class="blockList">
<li class="blockList"><a name="methods.inherited.from.class.cn.nukkit.level.generator.object.tree.TreeGenerator">
<!--   -->
</a>
<h3>继承自类 cn.nukkit.level.generator.object.tree.<a  title="class in cn.nukkit.level.generator.object.tree">TreeGenerator</a></h3>
<code><a >canGrowInto</a>, <a >generateSaplings</a>, <a >setDirtAt</a>, <a >setDirtAt</a></code></li>
</ul>
<ul class="blockList">
<li class="blockList"><a name="methods.inherited.from.class.cn.nukkit.level.generator.object.BasicGenerator">
<!--   -->
</a>
<h3>继承自类 cn.nukkit.level.generator.object.<a  title="class in cn.nukkit.level.generator.object">BasicGenerator</a></h3>
<code><a >generate</a>, <a >setBlock</a>, <a >setBlockAndNotifyAdequately</a>, <a >setBlockAndNotifyAdequately</a>, <a >setDecorationDefaults</a></code></li>
</ul>
<ul class="blockList">
<li class="blockList"><a name="methods.inherited.from.class.java.lang.Object">
<!--   -->
</a>
<h3>继承自类 java.lang.<a  title="class or interface in java.lang">Object</a></h3>
<code><a  title="class or interface in java.lang">clone</a>, <a  title="class or interface in java.lang">equals</a>, <a  title="class or interface in java.lang">finalize</a>, <a  title="class or interface in java.lang">getClass</a>, <a  title="class or interface in java.lang">hashCode</a>, <a  title="class or interface in java.lang">notify</a>, <a  title="class or interface in java.lang">notifyAll</a>, <a  title="class or interface in java.lang">toString</a>, <a  title="class or interface in java.lang">wait</a>, <a  title="class or interface in java.lang">wait</a>, <a  title="class or interface in java.lang">wait</a></code></li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
