# Unified-Time-Framework-UTF-ontology

UTF ontology is a unified time framework in geoscience systems.

In general, it consists of four parts: a root class to link all kinds of relevant time elements about the object, some general classes, such as time type, time reference, time relation, and et al., several description attributes in each class, for example, “Point_time” class has the attributes of point_id, point_value, point_unit, point_uncertainty, and et al., and some attribute interfaces to link to external ontologies, such as the reference_system attribute can link to existing geological time ontologies. In specific, there are five typical features of the UTF structure to achieve unified temporal information expression accurately and efficiently.

# An independent time root node. 
To avoid irrelevant attributes when time calculating, the UTF designs an independent time root node to link to the object. All the relevant time elements organize a time root node, which can be accessed and calculated directly. The time root includes the essential attributes, including id, type, description, expression, reference, and dating method information. 
# Different time types. 
To adapt to the time expression of different geoscience disciplines, the UTF designs three types of time expressions: Point, Interval, and Combination. Point time refers to the time moment, the fundamental statement of all geoscience knowledge. It stores point values and units and records the uncertainties and uncertainty units of these values. The interval time includes two Point times: a start and an end. It is noted that the interval direction also needs to be recorded because the direction affects the time calculation. The third type is combination time that indicates a set of points and intervals. Thus, it consists of id, point_number, point_set, interval_number, and interval_set. 
# Unified time nodes and structure. 
To achieve time calculation across different time elements, such as time reference, time unit, time dating method et al., the UTF designs a unified structure to record the time elements. This unified structure supports that all the time calculations have the same queries without estimating whether the nodes indicate the same time elements. It can significantly boost the performance of time calculation across different time elements.
# Quantitative relationship definitions. 
To ensure the accuracy of time expressions, the UTF defines the direct quantitative relationships between the time elements. The explicit quantitative relationships let the time expression have more accurate descriptions to eliminate redundant temporal information errors. 
# Adequate interfaces to external ontologies. 
To link to the external ontologies, the UTF sets some interface attributes that can cite the required and existing ontologies. For example, the attribute of reference_system can cite different external framework ontologies. Moreover, relation_system, unit_system, and dating_method can also link to the required ontologies. This structure lets the UTF become a platform to link to current ontologies.

More details can be email to wangshu@igsnrr.ac.cn.
