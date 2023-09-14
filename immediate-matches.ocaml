let rec fac = function
  | (0, acc) -> acc
  | (n, acc) -> fac (n - 1, n * acc) ;;

fac (7, 1) ;; (* 5040 *)

let rec fact = function
  | 0 -> fun acc -> acc
  | n -> fun acc -> fact (n - 1) (n * acc) ;;

fact 7 1 ;; (* 5040 *)
