---
layout: sidebar
sidebar: s1
version: "v3"
title: "att.harm.log"
---
<div class="classSpec att">
   <h3 id="att.harm.log">att.harm.log</h3>
   <table class="wovenodd">
      <tr>
         <td colspan="2" class="wovenodd-col2">Logical domain attributes.</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Module</strong></td>
         <td class="wovenodd-col2">MEI.harmony</td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Members</strong></td>
         <td class="wovenodd-col2">
            <div class="parent">
               <div><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/harm.html">harm</a> (direct member of att.harm.log)
               </div>
            </div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Attributes</strong></td>
         <td class="wovenodd-col2">
            <div class="attributeDef"><span class="attribute"><strong>@chordref</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Contains a reference to a &lt;chordDef&gt; element elsewhere in the document.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.harm.log.html">att.harm.log</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@dots</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Records the number of augmentation dots required by a dotted duration.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.augmentdot.html">data.AUGMENTDOT</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.augmentdots.html">att.augmentdots</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@dur</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Records duration using optionally dotted, relative durational values provided by the
                  data.DURATION datatype. When the duration is "irrational", as is sometimes the case
                  with
                  tuplets, multiple space-separated values that add up to the total duration may be
                  used.
                  When dotted values are present, the dots attribute must be ignored.</span>
               One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.duration.additive.html">data.DURATION.additive</a>, separated by spaces.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.duration.additive.html">att.duration.additive</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@endid</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Indicates the final element in a sequence of events to which the feature
                  applies.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.startendid.html">att.startendid</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@evaluate</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Specifies the intended meaning when a participant in a relationship is itself a
                  pointer.</span>
               Allowed values are:
               "<span style="font-weight: 500;">all</span>" <i>(If an element pointed to is itself a pointer, then the target of that pointer
                  will be taken, and so on, until an element is found which is not a pointer.)</i>,  "<span style="font-weight: 500;">one</span>" <i>(If an element pointed to is itself a pointer, then its target (whether a pointer
                  or not) is taken as the target of this pointer.)</i>,  "<span style="font-weight: 500;">none</span>" <i>(No further evaluation of targets is carried out beyond that needed to find the
                  element(s) specified in plist or target attribute.)</i><span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.targeteval.html">att.targeteval</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@layer</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Identifies the layer to which a feature applies.</span>
               One or more values of datatype <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.layerident.html">att.layerident</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@plist</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Contains a space separated list of references that identify active participants in
                  a
                  collection/relationship, such as notes under a phrase mark; that is, the entities
                  pointed "from".</span>
               One or more values from <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>, separated by spaces.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.plist.html">att.plist</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@staff</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Signifies the staff on which a notated event occurs or to which a control event
                  applies. Mandatory when applicable.</span>
               One or more values of datatype <span style="font-weight: 500;">positiveInteger</span>, separated by spaces.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.staffident.html">att.staffident</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@startid</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Holds a reference to the first element in a sequence of events to which the feature
                  applies.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.startid.html">att.startid</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@tstamp</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Encodes the onset time in terms of musical time, i.e.,
                  beats[.fractional_beat_part].</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.beat.html">data.BEAT</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.musical.html">att.timestamp.musical</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@tstamp.ges</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Captures performed onset time in several forms; that is, ppq (MIDI clicks and
                  MusicXML 'divisions'), Humdrum **recip values, beats, seconds, or mensural duration
                  values.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.duration.gestural.html">data.DURATION.gestural</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.performed.html">att.timestamp.performed</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@tstamp.real</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Used to record the onset time in terms of ISO time.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.isotime.html">data.ISOTIME</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp.performed.html">att.timestamp.performed</a></span></div>
            <div class="attributeDef"><span class="attribute"><strong>@tstamp2</strong></span><span class="attributeUsage">(optional)</span><span class="attributeDesc">Encodes the ending point of an event in terms of musical time, i.e., a count of
                  measures plus a beat location.</span>
               Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.measurebeat.html">data.MEASUREBEAT</a>.
               <span class="attributeClasses"><a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp2.musical.html">att.timestamp2.musical</a></span></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Declaration</strong></td>
         <td class="wovenodd-col2">
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classes&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.controlevent.html">att.controlevent</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.augmentdots.html">att.augmentdots</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.duration.additive.html">att.duration.additive</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.startendid.html">att.startendid</a>"</span></span>/&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;memberOf
                           <span class="attribute">key=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.timestamp2.musical.html">att.timestamp2.musical</a>"</span></span>/&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/classes&gt;</span></div></code></div>
            <div class="code" xml:space="preserve" data-lang="ODD"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"chordref"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Contains a reference to a &lt;chordDef&gt; element elsewhere in the document.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;datatype <span class="attribute">maxOccurs=</span><span class="attributevalue">"1"</span> <span class="attribute">minOccurs=</span><span class="attributevalue">"1"</span>&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;rng:ref
                              
                              <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.uri.html">data.URI</a>"</span></span>
                              /&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/datatype&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;constraintSpec <span class="attribute">ident=</span><span class="attributevalue">"check_chordrefTarget"</span> <span class="attribute">scheme=</span><span class="attributevalue">"isoschematron"</span>&gt;</span>
                        
                        <div class="indent3 indent"><span data-indentation="3" class="element">&lt;constraint&gt;</span>
                           
                           <div class="indent4 indent"><span data-indentation="4" class="element">&lt;sch:rule <span class="attribute">context=</span><span class="attributevalue">"@chordref"</span>&gt;</span>
                              
                              <div class="indent5 indent"><span data-indentation="5" class="element">&lt;sch:assert <span class="attribute">role=</span><span class="attributevalue">"warning"</span> <span class="attribute">test=</span><span class="attributevalue">"not(normalize-space(.) eq '')"</span>&gt;</span>@chordref attribute
                                 should have content.<span data-indentation="5" class="element">&lt;/sch:assert&gt;</span></div>
                              
                              <div class="indent5 indent"><span data-indentation="5" class="element">&lt;sch:assert <span class="attribute">role=</span><span class="attributevalue">"warning"</span> <span class="attribute">test=</span><span class="attributevalue">"every $i in tokenize(., '\s+') satisfies substring($i,2)=//mei:chordDef/@xml:id"</span>&gt;</span>The value in @chordref should correspond to the @xml:id attribute of a chordDef
                                 element.<span data-indentation="5" class="element">&lt;/sch:assert&gt;</span></div>
                              <span data-indentation="4" class="element">&lt;/sch:rule&gt;</span></div>
                           <span data-indentation="3" class="element">&lt;/constraint&gt;</span></div>
                        <span data-indentation="2" class="element">&lt;/constraintSpec&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/attDef&gt;</span></div></code></div>
         </td>
      </tr>
      <tr>
         <td class="wovenodd-col1"><strong>Constraint</strong></td>
         <td class="wovenodd-col2">
            <div>
               <div class="schematronText">@chordref attribute should have content.</div>
               <div class="schematronText">The value in @chordref should correspond to the @xml:id attribute of a chordDef element.</div>
            </div>
            <div class="code" xml:space="preserve" data-lang="Schematron"><code>
                  <div class="indent1 indent"><span data-indentation="1" class="element">&lt;sch:rule <span class="attribute">context=</span><span class="attributevalue">"@chordref"</span>&gt;</span>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;sch:assert <span class="attribute">role=</span><span class="attributevalue">"warning"</span> <span class="attribute">test=</span><span class="attributevalue">"not(normalize-space(.) eq '')"</span>&gt;</span>@chordref attribute
                        should have content.<span data-indentation="2" class="element">&lt;/sch:assert&gt;</span></div>
                     
                     <div class="indent2 indent"><span data-indentation="2" class="element">&lt;sch:assert <span class="attribute">role=</span><span class="attributevalue">"warning"</span> <span class="attribute">test=</span><span class="attributevalue">"every $i in tokenize(., '\s+') satisfies substring($i,2)=//mei:chordDef/@xml:id"</span>&gt;</span>The value in @chordref should correspond to the @xml:id attribute of a chordDef
                        element.<span data-indentation="2" class="element">&lt;/sch:assert&gt;</span></div>
                     <span data-indentation="1" class="element">&lt;/sch:rule&gt;</span></div></code></div>
         </td>
      </tr>
   </table>
</div>