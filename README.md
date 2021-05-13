# transformer-generator-notebook

We aim at showing that the usage of Transformer language model can be employed in Italian poetry text generation. We show two models, one that syllabifies and inserts caesura in any Italian hendecasyllable, and one that generates syllabified text with caesura in Dante's Divine Comedy style.

# Demo of generated text  

SEED   
```
  1 Vergine Madre, figlia del tuo figlio,    
  2 umile e alta più che creatura,  
  3 termine fisso d’ etterno consiglio,  
  4 tu se’ colei che l' umana natura  
  5 nobilitasti sì, che 'l suo fattore  
  6 non disdegnò di farsi sua fattura.
```

GENERATION  
```
  |que|sto |cie|lo |non<c> |ha |al|tro |ver |spe|so  
  |che |fa |dal |mez|zo<c> |non |so |ma |pa|ü|ra  
  |del |sol |più |vol|le |non<c> |per|do|na |guer|ra  

  |di |ra|gio|na|re an|cor<c> |vo' |mi |tuoi |pen|sa   
  |de |lo |pas|so<c> |de |vol|ger |ch' un |ghie |smor|to   
  |vi|di |lor<c> |a |es|ser |vol|ta |ra|mi|glia    

  |a |la |bat|ta|glia |le<c> |su|stan|ze |prie|ri  
  |che |non |ci |va<c> |per |un |mo|do |dif|fu|so  
  |a|mor |te|men|te<c> |dis|se |la |pro|pri|a  

  |a |te |mio |tan|to |so<c> |non |è |uo|mo |dio  
  |fu |già |tal |quan|do |ché<c> |po|ca |fa |gio|ia  
  |tuo |sol |per |sé<c> |la |mia |no|stra |men|zo|gna  
```

## Embedding Space Projection

<p align='center'>
  <img src="resources/embedding.gif" width="80%"/>
</p>


