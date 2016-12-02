<!SLIDE >
# Writing a Bot

    (defn action-ctx [db game]
      {})
    
    (defn actor-score-fn [db game ctx]
      (fn [actor]
        (rand-int 200)))
    
    (defn base-action-score-fn [db game ctx base]
      (fn [action]
        (rand-int 200)))
    
    (defn unit-action-score-fn [db game ctx unit]
      (fn [action]
        (rand-int 200)))


~~~SECTION:notes~~~
Demo: boot dev, enabling AI, editing custom-ai.
~~~ENDSECTION~~~
