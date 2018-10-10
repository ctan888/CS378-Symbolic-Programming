# cs378.clj
Files:

cs378.clj

; cs378.clj                Gordon S. Novak Jr.       04 Oct 18

; (load-file "/u/novak/cs378/cs378.clj")
;                    tst.xyz.core
(ns user
  (:use clojure.test )
  (:require [clojure.string :as str] ))
;            [clojure.math.numeric-tower :as math]

(def lstnum '(85 90 85 96 86 83 86 88 84 82 66 71 98 76 75 98 88 85))

; test whether x is a cons
(defn consb? [x] (and (seq? x) (not (empty? x))))

(defmacro cons? [x]
  (if (seq? x)
      (list 'consb? x)
      (list 'and (list 'seq? x) (list 'not (list 'empty? x)))))

formulas.clj

test3.clj

asgtest.java

Please check my personal blog for files above. Thanks.
