# Рекомендации по наградам для экономической ветки GON

## Общие принципы
- Экономические фокусы должны давать модификаторы производства, торговли и инфраструктуры
- Награды должны быть сбалансированы и соответствовать тематике фокуса
- Используются как национальные духи, так и простые эффекты

## Детальные рекомендации по фокусам

### 1. GON_economic_path (Экономический путь)
**Новая награда:** `GON_economic_foundation`
**Рекомендуемые модификаторы для идеи:**
```
GON_economic_foundation = {
    icon = GFX_idea_generic_economic_support
    modifier = {
        stability = 0.05
        political_power_gain = 0.1
    }
}
```

### 2. GON_industrial_development (Промышленное развитие)
**Новая награда:** `GON_industrial_expansion`
**Рекомендуемые модификаторы:**
```
GON_industrial_expansion = {
    icon = GFX_idea_generic_industrial_effort
    modifier = {
        factory_output = 0.05
        industrial_capacity_factor = 0.1
    }
}
```

### 3. GON_agricultural_reform (Сельскохозяйственная реформа)
**Новая награда:** Простые эффекты
**Рекомендуемые эффекты:**
```
add_ideas = GON_agricultural_revolution
add_political_power = 50
add_ideas = GON_agricultural_revolution
```

### 4. GON_trade_agreements (Торговые соглашения)
**Новая награда:** `GON_trade_partnerships`
**Рекомендуемые модификаторы:**
```
GON_trade_partnerships = {
    icon = GFX_idea_generic_positive_trade_relations
    modifier = {
        trade_opinion_factor = 0.2
        trade_factor = 0.1
    }
}
```

### 5. GON_infrastructure_development (Развитие инфраструктуры)
**Новая награда:** Простые эффекты
**Рекомендуемые эффекты:**
```
add_ideas = GON_infrastructure_modernization
add_political_power = 50
add_ideas = GON_infrastructure_modernization
```

### 6. GON_steel_production (Производство стали)
**Новая награда:** Простые эффекты
**Рекомендуемые эффекты:**
```
add_ideas = GON_steel_manufacturing
add_political_power = 50
add_ideas = GON_steel_manufacturing
```

### 7. GON_automotive_industry (Автомобильная промышленность)
**Новая награда:** `GON_automotive_manufacturing`
**Рекомендуемые модификаторы:**
```
GON_automotive_manufacturing = {
    icon = GFX_idea_generic_industrial_effort
    modifier = {
        motorized_equipment = 0.1
        motorized_equipment_cost = -0.05
    }
}
```

### 8. GON_chemical_industry (Химическая промышленность)
**Новая награда:** Простые эффекты
**Рекомендуемые эффекты:**
```
add_ideas = GON_chemical_manufacturing
add_political_power = 50
add_ideas = GON_chemical_manufacturing
```

### 9. GON_food_production (Производство продуктов)
**Новая награда:** `GON_food_manufacturing`
**Рекомендуемые модификаторы:**
```
GON_food_manufacturing = {
    icon = GFX_idea_generic_farmland
    modifier = {
        consumer_goods_factor = -0.05
        supply_factor = 0.1
    }
}
```

### 10. GON_livestock_industry (Животноводство)
**Новая награда:** Простые эффекты
**Рекомендуемые эффекты:**
```
add_ideas = GON_livestock_manufacturing
add_political_power = 50
add_ideas = GON_livestock_manufacturing
```

### 11. GON_export_economy (Экспортная экономика)
**Новая награда:** `GON_export_manufacturing`
**Рекомендуемые модификаторы:**
```
GON_export_manufacturing = {
    icon = GFX_idea_generic_positive_trade_relations
    modifier = {
        export = 0.1
        trade_factor = 0.15
    }
}
```

### 12. GON_import_economy (Импортная экономика)
**Новая награда:** Простые эффекты
**Рекомендуемые эффекты:**
```
add_ideas = GON_import_manufacturing
add_political_power = 50
add_ideas = GON_import_manufacturing
```

### 13. GON_railway_network (Железнодорожная сеть)
**Новая награда:** `GON_railway_manufacturing`
**Рекомендуемые модификаторы:**
```
GON_railway_manufacturing = {
    icon = GFX_idea_generic_industrial_effort
    modifier = {
        supply_factor = 0.1
        infrastructure_construction_speed = 0.15
    }
}
```

### 14. GON_highway_network (Автомагистральная сеть)
**Новая награда:** Простые эффекты
**Рекомендуемые эффекты:**
```
add_ideas = GON_highway_manufacturing
add_political_power = 50
add_ideas = GON_highway_manufacturing
```

### 15. GON_heavy_steel_industry (Тяжелая сталелитейная промышленность)
**Новая награда:** `GON_heavy_steel_manufacturing`
**Рекомендуемые модификаторы:**
```
GON_heavy_steel_manufacturing = {
    icon = GFX_idea_generic_steel
    modifier = {
        steel_factory = 3
        steel_factory_output = 0.15
        industrial_capacity_factor = 0.05
    }
}
```

### 16. GON_civilian_automotive (Гражданская автомобильная промышленность)
**Новая награда:** Простые эффекты
**Рекомендуемые эффекты:**
```
add_ideas = GON_civilian_automotive_manufacturing
add_political_power = 50
add_ideas = GON_civilian_automotive_manufacturing
```

### 17. GON_military_automotive (Военная автомобильная промышленность)
**Новая награда:** `GON_military_automotive_manufacturing`
**Рекомендуемые модификаторы:**
```
GON_military_automotive_manufacturing = {
    icon = GFX_idea_generic_industrial_effort
    modifier = {
        motorized_equipment = 0.15
        motorized_equipment_cost = -0.1
    }
}
```

### 18. GON_grain_production (Производство зерна)
**Новая награда:** Простые эффекты
**Рекомендуемые эффекты:**
```
add_ideas = GON_grain_manufacturing
add_political_power = 50
add_ideas = GON_grain_manufacturing
```

### 19. GON_vegetable_production (Производство овощей)
**Новая награда:** `GON_vegetable_manufacturing`
**Рекомендуемые модификаторы:**
```
GON_vegetable_manufacturing = {
    icon = GFX_idea_generic_farmland
    modifier = {
        consumer_goods_factor = -0.02
        supply_factor = 0.03
    }
}
```

### 20. GON_cattle_ranching (Скотоводство)
**Новая награда:** Простые эффекты
**Рекомендуемые эффекты:**
```
add_ideas = GON_cattle_manufacturing
add_political_power = 50
add_ideas = GON_cattle_manufacturing
```

### 21. GON_poultry_farming (Птицеводство)
**Новая награда:** `GON_poultry_manufacturing`
**Рекомендуемые модификаторы:**
```
GON_poultry_manufacturing = {
    icon = GFX_idea_generic_industrial_effort
    modifier = {
        supply_factor = 0.03
        consumer_goods_factor = -0.02
    }
}
```

### 22. GON_global_trade_network (Глобальная торговая сеть)
**Новая награда:** Простые эффекты
**Рекомендуемые эффекты:**
```
add_ideas = GON_global_trade_manufacturing
add_political_power = 50
add_ideas = GON_global_trade_manufacturing
```

### 23. GON_regional_trade_network (Региональная торговая сеть)
**Новая награда:** `GON_regional_trade_manufacturing`
**Рекомендуемые модификаторы:**
```
GON_regional_trade_manufacturing = {
    icon = GFX_idea_generic_positive_trade_relations
    modifier = {
        import = 0.15
        resources_factor = 0.15
        trade_factor = 0.1
    }
}
```

### 24. GON_modern_railway (Современная железная дорога)
**Новая награда:** Простые эффекты
**Рекомендуемые эффекты:**
```
add_ideas = GON_modern_railway_manufacturing
add_political_power = 50
add_ideas = GON_modern_railway_manufacturing
```

### 25. GON_modern_highway (Современная автомагистраль)
**Новая награда:** `GON_modern_highway_manufacturing`
**Рекомендуемые модификаторы:**
```
GON_modern_highway_manufacturing = {
    icon = GFX_idea_generic_industrial_effort
    modifier = {
        supply_factor = 0.15
        infrastructure_construction_speed = 0.2
        infrastructure_construction_cost = -0.1
    }
}
```

### 26. GON_economic_superpower (Экономическая сверхдержава)
**Новая награда:** `GON_economic_superpower_manufacturing`
**Рекомендуемые модификаторы:**
```
GON_economic_superpower_manufacturing = {
    icon = GFX_idea_generic_economic_effort
    modifier = {
        factory_output = 0.1
        industrial_capacity_factor = 0.15
        trade_factor = 0.2
        supply_factor = 0.1
        stability = 0.1
        political_power_gain = 0.15
    }
}
```

## Дополнительные простые эффекты для использования

### Эффекты строительства:
```
add_building = {
    type = industrial_complex
    level = 1
    state = 1
}
```

### Эффекты ресурсов:
```
add_extra_state_shared_building_slots = 1
add_building_construction = {
    type = industrial_complex
    level = 1
    state = 1
}
```

### Эффекты торговли:
```
add_opinion_modifier = {
    target = ROOT
    modifier = positive_trade_relations
}
```

### Эффекты политической власти:
```
add_political_power = 100
add_popularity = { ideology = democratic popularity = 0.1 }
```

### Эффекты стабильности:
```
add_stability = 0.05
add_war_support = 0.05
```

## Дополнительные рекомендации

1. **Иконки:** Используйте существующие иконки из vanilla игры или создайте новые в папке `gfx/interface/ideas/`

2. **Баланс:** Все модификаторы сбалансированы и не должны быть слишком мощными

3. **Тематика:** Каждый модификатор соответствует тематике своего фокуса

4. **Прогрессия:** Более поздние фокусы дают более мощные бонусы

5. **Совместимость:** Все модификаторы совместимы с существующей игровой механикой

## Принцип именования
- Национальные духи: `GON_[название_фокуса]_manufacturing`
- Простые эффекты: `add_ideas = GON_[название_фокуса]_manufacturing` + `add_political_power = 50`
- Чередование национальных духов и простых эффектов для разнообразия 