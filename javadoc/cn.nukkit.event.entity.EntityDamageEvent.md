<div class="summary">
<ul class="blockList">
<li class="blockList">
<!-- ======== NESTED CLASS SUMMARY ======== -->
<ul class="blockList">
<li class="blockList"><a name="nested.class.summary">
<!--   -->
</a>
<h3>Nested Class Summary</h3>
<table class="memberSummary" border="0" cellpadding="3" cellspacing="0" summary="Nested Class Summary table, listing nested classes, and an explanation">
<caption><span>Nested Classes</span><span class="tabEnd"> </span></caption>
<tr>
<th>修饰符和类</th>
<th class="colLast" scope="col">Class and Description</th>
</tr>
<tr class="altColor">
<td class="colFirst"><code>static class </code></td>
<td class="colLast"><code><span class="memberNameLink"><a  title="enum in cn.nukkit.event.entity">EntityDamageEvent.DamageCause</a></span></code> </td>
</tr>
<tr class="rowColor">
<td class="colFirst"><code>static class </code></td>
<td class="colLast"><code><span class="memberNameLink"><a  title="enum in cn.nukkit.event.entity">EntityDamageEvent.DamageModifier</a></span></code> </td>
</tr>
</table>
</li>
</ul>  
<li class="blockList"><a name="field.summary">
<!--   -->
</a>
<h3>成员变量一览</h3>
<ul class="blockList">
<li class="blockList"><a name="fields.inherited.from.class.cn.nukkit.event.entity.EntityEvent">
<!--   -->
</a>
<h3>继承自类 cn.nukkit.event.entity.<a  title="class in cn.nukkit.event.entity">EntityEvent</a></h3>
<code><a >entity</a></code></li>
</ul>
<ul class="blockList">
<li class="blockList"><a name="fields.inherited.from.class.cn.nukkit.event.Event">
<!--   -->
</a>
<h3>继承自类 cn.nukkit.event.<a  title="class in cn.nukkit.event">Event</a></h3>
<code><a >eventName</a></code></li>
</ul>
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
<td class="colOne"><code><span class="memberNameLink"><a >EntityDamageEvent</a></span>(<a  title="class in cn.nukkit.entity">Entity</a> entity,
                 <a  title="enum in cn.nukkit.event.entity">EntityDamageEvent.DamageCause</a> cause,
                 float damage)</code> </td>
</tr>
<tr class="rowColor">
<td class="colOne"><code><span class="memberNameLink"><a >EntityDamageEvent</a></span>(<a  title="class in cn.nukkit.entity">Entity</a> entity,
                 <a  title="enum in cn.nukkit.event.entity">EntityDamageEvent.DamageCause</a> cause,
                 <a  title="class or interface in java.util">Map</a>&lt;<a  title="enum in cn.nukkit.event.entity">EntityDamageEvent.DamageModifier</a>,<a  title="class or interface in java.lang">Float</a>&gt; modifiers)</code> </td>
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
<caption><span id="t0" class="activeTableTab"><span>All Methods</span><span class="tabEnd"> </span></span><span id="t1" class="tableTab"><span><a >Static Methods</a></span><span class="tabEnd"> </span></span><span id="t2" class="tableTab"><span><a >Instance Methods</a></span><span class="tabEnd"> </span></span><span id="t4" class="tableTab"><span><a >Concrete Methods</a></span><span class="tabEnd"> </span></span></caption>
<tr>
<th>修饰符和类</th>
<th>成员函数描述</th>
</tr>
<tr id="i0" class="altColor">
<td class="colFirst"><code>boolean</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >canBeReducedByArmor</a></span>()</code> </td>
</tr>
<tr id="i1" class="rowColor">
<td class="colFirst"><code>int</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getAttackCooldown</a></span>()</code> </td>
</tr>
<tr id="i2" class="altColor">
<td class="colFirst"><code><a  title="enum in cn.nukkit.event.entity">EntityDamageEvent.DamageCause</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getCause</a></span>()</code> </td>
</tr>
<tr id="i3" class="rowColor">
<td class="colFirst"><code>float</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getDamage</a></span>()</code> </td>
</tr>
<tr id="i4" class="altColor">
<td class="colFirst"><code>float</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getDamage</a></span>(<a  title="enum in cn.nukkit.event.entity">EntityDamageEvent.DamageModifier</a> type)</code> </td>
</tr>
<tr id="i5" class="rowColor">
<td class="colFirst"><code>float</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getFinalDamage</a></span>()</code> </td>
</tr>
<tr id="i6" class="altColor">
<td class="colFirst"><code>static <a  title="class in cn.nukkit.event">HandlerList</a></code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getHandlers</a></span>()</code> </td>
</tr>
<tr id="i7" class="rowColor">
<td class="colFirst"><code>float</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getOriginalDamage</a></span>()</code> </td>
</tr>
<tr id="i8" class="altColor">
<td class="colFirst"><code>float</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >getOriginalDamage</a></span>(<a  title="enum in cn.nukkit.event.entity">EntityDamageEvent.DamageModifier</a> type)</code> </td>
</tr>
<tr id="i9" class="rowColor">
<td class="colFirst"><code>boolean</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >isApplicable</a></span>(<a  title="enum in cn.nukkit.event.entity">EntityDamageEvent.DamageModifier</a> type)</code> </td>
</tr>
<tr id="i10" class="altColor">
<td class="colFirst"><code>void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >setAttackCooldown</a></span>(int attackCooldown)</code> </td>
</tr>
<tr id="i11" class="rowColor">
<td class="colFirst"><code>void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >setDamage</a></span>(float damage)</code> </td>
</tr>
<tr id="i12" class="altColor">
<td class="colFirst"><code>void</code></td>
<td class="colLast"><code><span class="memberNameLink"><a >setDamage</a></span>(float damage,
         <a  title="enum in cn.nukkit.event.entity">EntityDamageEvent.DamageModifier</a> type)</code> </td>
</tr>
</table>
<ul class="blockList">
<li class="blockList"><a name="methods.inherited.from.class.cn.nukkit.event.entity.EntityEvent">
<!--   -->
</a>
<h3>继承自类 cn.nukkit.event.entity.<a  title="class in cn.nukkit.event.entity">EntityEvent</a></h3>
<code><a >getEntity</a></code></li>
</ul>
<ul class="blockList">
<li class="blockList"><a name="methods.inherited.from.class.cn.nukkit.event.Event">
<!--   -->
</a>
<h3>继承自类 cn.nukkit.event.<a  title="class in cn.nukkit.event">Event</a></h3>
<code><a >getEventName</a>, <a >isCancelled</a>, <a >setCancelled</a>, <a >setCancelled</a></code></li>
</ul>
<ul class="blockList">
<li class="blockList"><a name="methods.inherited.from.class.java.lang.Object">
<!--   -->
</a>
<h3>继承自类 java.lang.<a  title="class or interface in java.lang">Object</a></h3>
<code><a  title="class or interface in java.lang">clone</a>, <a  title="class or interface in java.lang">equals</a>, <a  title="class or interface in java.lang">finalize</a>, <a  title="class or interface in java.lang">getClass</a>, <a  title="class or interface in java.lang">hashCode</a>, <a  title="class or interface in java.lang">notify</a>, <a  title="class or interface in java.lang">notifyAll</a>, <a  title="class or interface in java.lang">toString</a>, <a  title="class or interface in java.lang">wait</a>, <a  title="class or interface in java.lang">wait</a>, <a  title="class or interface in java.lang">wait</a></code></li>
</ul>
<ul class="blockList">
<li class="blockList"><a name="methods.inherited.from.class.cn.nukkit.event.Cancellable">
<!--   -->
</a>
<h3>继承自接口 cn.nukkit.event.<a  title="interface in cn.nukkit.event">Cancellable</a></h3>
<code><a >isCancelled</a>, <a >setCancelled</a>, <a >setCancelled</a></code></li>
</ul>
</li>
</ul>
</li>
</ul>
</div>