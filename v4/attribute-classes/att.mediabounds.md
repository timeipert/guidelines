---
layout: sidebar
sidebar: s1
version: "v4"
title: "att.mediaBounds"
---
<div class="specPage">
   <div class="attClassSpec">
      <h3 id="att.mediaBounds">att.mediaBounds</h3>
      <div class="specs">
         <div class="desc">Attributes that establish the boundaries of a media object.</div>
         <div class="facet module">
            <div class="label">Module</div>
            <div class="statement text">MEI.shared</div>
         </div>
         <div class="facet attributes" id="attributes">
            <div class="label">Attributes</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="attributes_compact_tab" href="#attributes" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="full" id="attributes_full_tab" href="#attributes" class="displayTab">full definition</a></li>
                  <li class="tab-item"><a data-display="class" id="attributes_class_tab" href="#attributes" class="displayTab">by class</a></li>
                  <li class="tab-item"><a data-display="module" id="attributes_module_tab" href="#attributes" class="displayTab">by module</a></li>
               </ul>
               <div id="attributes_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident attribute" title="Specifies a point where the relevant content begins. A numerical value must be less and a time value must be earlier than that given by the end attribute.">begin</span>, <span class="ident attribute" title="Type of values used in the begin/end attributes. The begin and end attributes can only be interpreted meaningfully in conjunction with this attribute.">betype</span>, <span class="ident attribute" title="Specifies a point where the relevant content ends. If not specified, the end of the content is assumed to be the end point. A numerical value must be greater and a time value must be later than that given by the begin attribute.">end</span></div>
               <div id="attributes_tabbedContent_full" class="facetTabbedContent full">
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Specifies a point where the relevant content begins. A numerical value must be less and a time value must be earlier than that given by the end attribute.">begin</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Specifies a point where the relevant content begins. A numerical value must be less
                        and a time value must be earlier than that given by the end attribute.</span><span class="attributeValues">
                        Value is plain text.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Type of values used in the begin/end attributes. The begin and end attributes can only be interpreted meaningfully in conjunction with this attribute.">betype</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Type of values used in the begin/end attributes. The begin and end attributes can
                        only
                        be interpreted meaningfully in conjunction with this attribute.</span><span class="attributeValues">
                        Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.betype.html">data.BETYPE</a>.
                        </span></div>
                  <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Specifies a point where the relevant content ends. If not specified, the end of the content is assumed to be the end point. A numerical value must be greater and a time value must be later than that given by the begin attribute.">end</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Specifies a point where the relevant content ends. If not specified, the end of the
                        content is assumed to be the end point. A numerical value must be greater and a time
                        value
                        must be later than that given by the begin attribute.</span><span class="attributeValues">
                        Value is plain text.
                        </span></div>
               </div>
               <div id="attributes_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox direct" title="direct childs">
                     <div class="classHeading"><label class="classLabel">direct childs</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Specifies a point where the relevant content begins. A numerical value must be less and a time value must be earlier than that given by the end attribute.">begin</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Specifies a point where the relevant content begins. A numerical value must be less
                              and a time value must be earlier than that given by the end attribute.</span><span class="attributeValues">
                              Value is plain text.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Specifies a point where the relevant content ends. If not specified, the end of the content is assumed to be the end point. A numerical value must be greater and a time value must be later than that given by the begin attribute.">end</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Specifies a point where the relevant content ends. If not specified, the end of the
                              content is assumed to be the end point. A numerical value must be greater and a time
                              value
                              must be later than that given by the begin attribute.</span><span class="attributeValues">
                              Value is plain text.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Type of values used in the begin/end attributes. The begin and end attributes can only be interpreted meaningfully in conjunction with this attribute.">betype</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Type of values used in the begin/end attributes. The begin and end attributes can
                              only
                              be interpreted meaningfully in conjunction with this attribute.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.betype.html">data.BETYPE</a>.
                              </span></div>
                     </div>
                  </div>
               </div>
               <div id="attributes_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.shared">
                     <div class="classHeading"><label class="classLabel">MEI.shared</label><span class="classDesc">Component declarations that are shared between two or more modules.</span></div>
                     <div class="classContent">
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Specifies a point where the relevant content begins. A numerical value must be less and a time value must be earlier than that given by the end attribute.">begin</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Specifies a point where the relevant content begins. A numerical value must be less
                              and a time value must be earlier than that given by the end attribute.</span><span class="attributeValues">
                              Value is plain text.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Type of values used in the begin/end attributes. The begin and end attributes can only be interpreted meaningfully in conjunction with this attribute.">betype</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Type of values used in the begin/end attributes. The begin and end attributes can
                              only
                              be interpreted meaningfully in conjunction with this attribute.</span><span class="attributeValues">
                              Value conforms to <a class="link_odd_classSpec" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.betype.html">data.BETYPE</a>.
                              </span></div>
                        <div class="attributeDef def" data-module="MEI.shared"><span class="ident attribute" title="Specifies a point where the relevant content ends. If not specified, the end of the content is assumed to be the end point. A numerical value must be greater and a time value must be later than that given by the begin attribute.">end</span><span class="attributeUsage">(optional)</span><span class="attributeDesc desc">Specifies a point where the relevant content ends. If not specified, the end of the
                              content is assumed to be the end point. A numerical value must be greater and a time
                              value
                              must be later than that given by the begin attribute.</span><span class="attributeValues">
                              Value is plain text.
                              </span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet availableAt" id="availableAt">
            <div class="label">Available at</div>
            <div class="statement classes list">
               <ul class="tab">
                  <li class="tab-item"><a data-display="compact" id="availableAt_compact_tab" href="#availableAt" class="displayTab active">compact</a></li>
                  <li class="tab-item"><a data-display="class" id="availableAt_class_tab" href="#availableAt" class="displayTab">by class</a></li>
                  <li class="tab-item"><a data-display="module" id="availableAt_module_tab" href="#availableAt" class="displayTab">by module</a></li>
               </ul>
               <div id="availableAt_tabbedContent_compact" class="facetTabbedContent compact active"><span class="ident element" title="Defines a time segment of interest within a recording or within a digital audio or video file."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/clip.html">clip</a></span>, <span class="ident element" title="A recorded performance."><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/recording.html">recording</a></span></div>
               <div id="availableAt_tabbedContent_class" class="facetTabbedContent class">
                  <div class="classBox" title="att.mediaBounds">
                     <div class="classHeading"><label class="classLabel"><a class="classLink" href="{{ site.baseurl }}/{{ page.version }}/attribute-classes/att.mediabounds.html">att.mediaBounds</a></label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.performance"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/clip.html">clip</a><span class="elementDesc">Defines a time segment of interest within a recording or within a digital audio or
                              video
                              file.</span></div>
                        <div class="elementRef" data-module="MEI.performance"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/recording.html">recording</a><span class="elementDesc">A recorded performance.</span></div>
                     </div>
                  </div>
               </div>
               <div id="availableAt_tabbedContent_module" class="facetTabbedContent module">
                  <div class="classBox" title="MEI.performance">
                     <div class="classHeading"><label class="classLabel">MEI.performance</label><span class="classDesc"></span></div>
                     <div class="classContent">
                        <div class="elementRef" data-module="MEI.performance"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/clip.html">clip</a><span class="elementDesc">Defines a time segment of interest within a recording or within a digital audio or
                              video
                              file.</span></div>
                        <div class="elementRef" data-module="MEI.performance"><a class="link_odd_elementSpec" href="{{ site.baseurl }}/{{ page.version }}/elements/recording.html">recording</a><span class="elementDesc">A recorded performance.</span></div>
                     </div>
                  </div>
               </div>
            </div>
         </div>
         <div class="facet declaration">
            <div class="label">Declaration</div>
            <div class="statement declaration">
               <div class="code" xml:space="preserve" data-lang="ODD"><code>
                     <div class="indent1 indent"><span data-indentation="1" class="element">&lt;classSpec <span class="attribute">ident=</span><span class="attributevalue">"att.mediaBounds"</span> <span class="attribute">module=</span><span class="attributevalue">"MEI.shared"</span> <span class="attribute">type=</span><span class="attributevalue">"atts"</span>&gt;</span>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;desc&gt;</span>Attributes that establish the boundaries of a media object.<span data-indentation="2" class="element">&lt;/desc&gt;</span></div>
                        
                        <div class="indent2 indent"><span data-indentation="2" class="element">&lt;attList&gt;</span>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"begin"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>Specifies a point where the relevant content begins. A numerical value must be less
                                 and a time value must be earlier than that given by the end attribute.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;datatype&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;rng:text/&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/datatype&gt;</span></div>
                              <span data-indentation="3" class="element">&lt;/attDef&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"end"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>Specifies a point where the relevant content ends. If not specified, the end of the
                                 content is assumed to be the end point. A numerical value must be greater and a time
                                 value
                                 must be later than that given by the begin attribute.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;datatype&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;rng:text/&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/datatype&gt;</span></div>
                              <span data-indentation="3" class="element">&lt;/attDef&gt;</span></div>
                           
                           <div class="indent3 indent"><span data-indentation="3" class="element">&lt;attDef <span class="attribute">ident=</span><span class="attributevalue">"betype"</span> <span class="attribute">usage=</span><span class="attributevalue">"opt"</span>&gt;</span>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;desc&gt;</span>Type of values used in the begin/end attributes. The begin and end attributes can
                                 only
                                 be interpreted meaningfully in conjunction with this attribute.<span data-indentation="4" class="element">&lt;/desc&gt;</span></div>
                              
                              <div class="indent4 indent"><span data-indentation="4" class="element">&lt;datatype&gt;</span>
                                 
                                 <div class="indent5 indent"><span data-indentation="5" class="element">&lt;rng:ref
                                       
                                       <span class="attribute">name=<span class="attributevalue">"<a class="link_odd" href="{{ site.baseurl }}/{{ page.version }}/data-types/data.betype.html">data.BETYPE</a>"</span></span>
                                       /&gt;</span></div>
                                 <span data-indentation="4" class="element">&lt;/datatype&gt;</span></div>
                              <span data-indentation="3" class="element">&lt;/attDef&gt;</span></div>
                           <span data-indentation="2" class="element">&lt;/attList&gt;</span></div>
                        <span data-indentation="1" class="element">&lt;/classSpec&gt;</span></div></code></div>
            </div>
         </div>
      </div><script type="text/javascript">
            
            var tabbedFacets = document.querySelectorAll('.facet ul.tab');
            
            var tabClick = function(e) {
                var style = e.target.getAttribute('data-display');
                var facetId = e.target.parentNode.parentNode.parentNode.parentNode.id;
                setTabs(facetId,style)
            }
            
            for(var facetUl of tabbedFacets) {
                var facetElem = facetUl.parentNode.parentNode;
                var facetId = facetElem.id;
                var storageName = 'meiSpecs_' + facetId + '_display';
                var defaultValue = facetUl.children[0].children[0].getAttribute('data-display');
                
                if(localStorage.getItem(storageName) === null) {
                    setTabs(facetElem.id,defaultValue);
                } else {
                    setTabs(facetElem.id,localStorage.getItem(storageName));
                }
                
                var tabs = facetUl.querySelectorAll('.tab-item a');
                
                for(var tab of tabs) {
                    tab.addEventListener('click',tabClick);
                }
                
            }
            
            function setTabs(facetId,style) {
                
                var storageName = 'meiSpecs_' + facetId + '_display';
                localStorage.setItem(storageName,style);
                
                var facetElem = document.getElementById(facetId);
                
                var oldTab = facetElem.querySelector('.displayTab.active');
                oldTab.classList.remove('active');
                
                var newTab = document.getElementById(facetId + '_' + style + '_tab');
                newTab.classList.add('active');
                
                var oldBox = facetElem.querySelector('.active.facetTabbedContent');
                oldBox.classList.remove('active');
                oldBox.style.display = 'none';
                
                var newBox = document.getElementById(facetId + '_tabbedContent_' + style);
                newBox.classList.add('active');
                newBox.style.display = 'block';
                
            }
        </script></div>
</div>